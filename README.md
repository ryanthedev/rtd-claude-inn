# RTD Claude Plugin Marketplace

A plugin marketplace for Claude Code.

## Installation

```bash
/plugin marketplace add ryanthedev/rtd-claude-inn
```

## Available Plugins

| Plugin | Version | Description |
|--------|---------|-------------|
| [oberskills](https://github.com/ryanthedev/oberskills) | 1.17.0 | Hypothesis-driven debugging, prompt engineering, agent dispatch, meta-planning, plan execution, web search, quick hack mode, and skill creation |
| [code-foundations](https://github.com/ryanthedev/code-foundations) | 3.0.0 | Software engineering skills with profile-driven code review and quality-gated execution |

### oberskills

Advanced Claude Code skills:

| Skill | Purpose |
|-------|---------|
| **oberdebug** | Hypothesis-driven debugging with evidence-based root cause analysis |
| **oberprompt** | Research-backed prompt engineering for LLM systems |
| **oberagent** | Enforces prompt engineering best practices before agent dispatch |
| **oberweb** | Multi-dimensional web search with file-based results and opus synthesis |
| **oberhack** | Quick hack mode - no ceremony, just GROK → DISPATCH → DONE |
| **obercreate** | Skill creation with pressure testing (RED-GREEN-REFACTOR) |
| ~~oberplan~~ | *Deprecated* - Use code-foundations:whiteboarding instead |
| ~~oberexec~~ | *Deprecated* - Use code-foundations:building instead |

### code-foundations

AI that codes like a senior engineer. Checklists, quality gates, and verification built into every workflow.

**Commands:**

| Command | Purpose |
|---------|---------|
| `/code-foundations:review` | Profile-driven code review (99-548 checks) |
| `/code-foundations:whiteboarding` | Create implementation-ready plans |
| `/code-foundations:building` | Execute plans with quality gates |
| `/code-foundations:code` | Pseudocode-first development |
| `/code-foundations:prototype` | Quick feasibility proof |
| `/code-foundations:debug` | Scientific debugging with task tracking |

**Code Review Profiles:**

| Profile | Checklists | Checks |
|---------|------------|--------|
| `--sanity` | 1 | 99 |
| `--pr` | 10 | 548 |
| Custom | varies | varies |

**Architecture:** Extraction → Checking (1 agent per checklist) → Investigation → Report

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
