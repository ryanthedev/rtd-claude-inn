# RTD Claude Plugin Marketplace

A plugin marketplace for Claude Code.

## Installation

```bash
/plugin marketplace add ryanthedev/rtd-claude-inn
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [oberskills](https://github.com/ryanthedev/oberskills) | Prompt engineering, agent dispatch enforcement, skill creation and review, screenshot analysis, web search, and human-sounding writing |
| [code-foundations](https://github.com/ryanthedev/code-foundations) | Software engineering skills distilled from the industry's favorite books. Checklist-driven code review, debugging, whiteboarding, and quality gates. |

Plugins track the `main` branch of their source repos. Versions are managed in each plugin's own `plugin.json`.

## Installing Plugins

```bash
# Install from marketplace
/plugin install oberskills@rtd
/plugin install code-foundations@rtd

# Update to latest version
/plugin update oberskills@rtd
/plugin update code-foundations@rtd
```

## Updating the Marketplace

```bash
/plugin marketplace update rtd
```
