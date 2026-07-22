# RTD Claude Plugin Marketplace

Plugins for Claude Code. Add the marketplace once, install what you need.

## Add the Marketplace

```bash
/plugin marketplace add ryanthedev/rtd-claude-inn
```

## Plugins

| Plugin | What it does |
|--------|-------------|
| [oberskills](https://github.com/ryanthedev/oberskills) | Prompt engineering, agent dispatch, skill creation, web search, and writing that sounds human |
| [code-foundations](https://github.com/ryanthedev/code-foundations) | Code review, debugging, whiteboarding, and quality gates drawn from the industry's go-to books |
| [design-for-ai](https://github.com/ryanthedev/design-for-ai) | A research → plan → mock → build design workflow with a composition dealer, dual-blind review, and gated artifacts |
| [react-native-foundations](https://github.com/ryanthedev/react-native-foundations.skill) | Doc search, iOS Simulator control, error diagnosis, runtime debugging, layout checks, and a11y auditing for React Native |
| [svelte-foundations](https://github.com/ryanthedev/svelte-foundations.skill) | Svelte/SvelteKit docs, browser automation, error diagnosis, coding guidance, and a11y auditing |
| [claude-mux](https://github.com/ryanthedev/claude-mux.mcp) | tmux control and multi-agent coordination — spawn workers, messaging, shared task lists |
| [grug-brain](https://github.com/ryanthedev/grug-brain.mcp) | Persistent memory with FTS5 search, docs indexing, dreaming, and shared brain sync |
| [penman](https://github.com/ryanthedev/penman) | Markdown to rich text for any platform — copies styled HTML to clipboard ready to paste |
| [what](https://github.com/ryanthedev/what-skills) | Four interrogation skills — requirements, options, blind spots, stress tests — each run by a fresh Fable 5 agent |
| [systems-design](https://github.com/ryanthedev/systems-design.skill) | Frameworks for system design interviews and architecture review of distributed systems |
| [herderp](https://github.com/ryanthedev/herderp) | herdr CLI as MCP tools, plus session necromancy — bring a dead Claude Code session back in a fresh pane |
| [sdd](https://github.com/ryanthedev/sdd) | Delegate scoped work to CLI harnesses (codex, grok, kimi, qwen, mistral, agy), fan out, collect structured results — plus a video-to-transcript pipeline |
| [siren](https://github.com/ryanthedev/siren) | Mermaid diagrams with a semantic color system, the silent-failure traps mapped, a 20-check preflight validator, and a no-build gallery template |

## Install

```bash
/plugin install oberskills@rtd
/plugin install code-foundations@rtd
/plugin install design-for-ai@rtd
/plugin install react-native-foundations@rtd
/plugin install svelte-foundations@rtd
/plugin install claude-mux@rtd
/plugin install grug-brain@rtd
/plugin install penman@rtd
/plugin install what@rtd
/plugin install systems-design@rtd
/plugin install herderp@rtd
/plugin install sdd@rtd
/plugin install siren@rtd
```

## Update

Refresh the marketplace listing:

```bash
/plugin marketplace update rtd
```

Pull the latest version of a plugin:

```bash
claude plugin update <plugin>@rtd    # e.g. claude plugin update sdd@rtd
```

All plugins track `main` on their source repos.
