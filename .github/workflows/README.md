# Marketplace Workflows

## bump-plugin-version.yml

Receives `repository_dispatch` events from plugin repos to update their version in the marketplace.

### Trigger Payload

```json
{
  "event_type": "plugin-version-bump",
  "client_payload": {
    "plugin_name": "oberskills",
    "version": "1.14.0",
    "changelog": "Added feature X\nFixed bug Y"
  }
}
```

### What it does

1. Validates the payload (plugin_name, version format)
2. Checks the plugin exists in `marketplace.json`
3. Updates the version
4. Commits the change
5. Creates a GitHub Release tagged `{plugin}-v{version}`

## Setting up a plugin repo

1. Create a GitHub Personal Access Token (PAT) with `repo` scope
2. Add it as a secret named `MARKETPLACE_DISPATCH_TOKEN` in your plugin repo
3. Copy the example workflow to your plugin repo:

```bash
# From your plugin repo
curl -o .github/workflows/notify-marketplace.yml \
  https://raw.githubusercontent.com/ryanthedev/rtd-claude-inn/main/.github/workflows/example-trigger-from-plugin-repo.yml.example
```

4. Edit `PLUGIN_NAME` in the workflow to match your plugin name
5. Create a release - the marketplace will auto-update!

## Manual trigger (for testing)

```bash
curl -X POST \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer YOUR_PAT" \
  https://api.github.com/repos/ryanthedev/rtd-claude-inn/dispatches \
  -d '{
    "event_type": "plugin-version-bump",
    "client_payload": {
      "plugin_name": "oberskills",
      "version": "1.14.0",
      "changelog": "Test release"
    }
  }'
```
