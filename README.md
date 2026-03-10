# RTD Claude Plugin Marketplace

Four plugins for Claude Code. Add the marketplace once, install what you need.

## Add the Marketplace

```bash
/plugin marketplace add ryanthedev/rtd-claude-inn
```

## Plugins

| Plugin | What it does |
|--------|-------------|
| [oberskills](https://github.com/ryanthedev/oberskills) | Prompt engineering, agent dispatch, skill creation, web search, and writing that sounds human |
| [code-foundations](https://github.com/ryanthedev/code-foundations) | Code review, debugging, whiteboarding, and quality gates drawn from the industry's go-to books |
| [design-for-ai](https://github.com/ryanthedev/design-for-ai) | Typography, color science, composition, and visual hierarchy from *Design for Hackers* |
| [react-native-foundations](https://github.com/ryanthedev/react-native-foundations.skill) | Doc search, iOS Simulator control, error diagnosis, runtime debugging, layout checks, and a11y auditing for React Native |

## Install

```bash
/plugin install oberskills@rtd
/plugin install code-foundations@rtd
/plugin install design-for-ai@rtd
/plugin install react-native-foundations@rtd
```

## Update

Refresh the marketplace listing:

```bash
/plugin marketplace update rtd
```

Pull the latest version of a plugin:

```bash
claude plugin update oberskills@rtd
claude plugin update code-foundations@rtd
claude plugin update design-for-ai@rtd
claude plugin update react-native-foundations@rtd
```

All plugins track `main` on their source repos.
