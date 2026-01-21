# RTD Claude Plugin Marketplace

A plugin marketplace for Claude Code.

## Installation

```bash
/plugin marketplace add ryanthedev/rtd-claude-inn
```

## Available Plugins

| Plugin | Version | Description |
|--------|---------|-------------|
| [oberskills](https://github.com/ryanthedev/oberskills) | 1.16.0 | Hypothesis-driven debugging, prompt engineering, agent dispatch, meta-planning, plan execution, web search, quick hack mode, and skill creation |
| [code-foundations](https://github.com/ryanthedev/code-foundations) | 2.7.3 | Software engineering skills from Code Complete & APOSD with three-level code review system |

### oberskills

Advanced Claude Code skills:

| Skill | Purpose |
|-------|---------|
| **oberdebug** | Hypothesis-driven debugging with evidence-based root cause analysis |
| **oberprompt** | Research-backed prompt engineering for LLM systems |
| **oberagent** | Enforces prompt engineering best practices before agent dispatch |
| **oberplan** | Meta-planning orchestration with lens skills and final review |
| **oberexec** | Subagent-driven plan executor with checkpoints and code reviews |
| **oberweb** | Multi-dimensional web search with parallel haiku subagents |
| **oberhack** | Quick hack mode - no ceremony, just GROK → DISPATCH → DONE |
| **obercreate** | Skill creation with pressure testing (RED-GREEN-REFACTOR) |

### code-foundations

Software engineering skills from Code Complete (McConnell) and A Philosophy of Software Design (Ousterhout):

**Code Review Commands:**

| Command | Level | Purpose |
|---------|-------|---------|
| `/check-commit` | Quick | Big-O, complexity, style, obvious bugs (~2 min) |
| `/review-changes` | Medium | Design, errors, correctness (~5-10 min) |
| `/review-pr` | Full | Multi-dimensional with parallel agents (~15-30 min) |

**Review Agents:**

| Agent | Focus |
|-------|-------|
| **security-reviewer** | Input validation, injection, auth, secrets |
| **performance-reviewer** | Big-O, algorithms, scaling |
| **maintainability-reviewer** | Complexity symptoms, cohesion, coupling |
| **error-handling-reviewer** | Silent failures, catch blocks |
| **clarity-reviewer** | Naming, comments, readability |
| **correctness-reviewer** | Boundaries, concurrency, edge cases |

**CC Skills (Process & Metrics):**

| Skill | Purpose |
|-------|---------|
| **code-foundations** | Master dispatcher with checklists |
| **cc-developer-character** | Mindset and discipline |
| **cc-routine-and-class-design** | Cohesion, coupling, inheritance |
| **cc-defensive-programming** | Error handling, validation |
| **cc-refactoring-guidance** | Safe refactoring process |
| **cc-quality-practices** | Testing, debugging, reviews |
| **cc-performance-tuning** | Measure-first optimization |

**APOSD Skills (Design Philosophy):**

| Skill | Purpose |
|-------|---------|
| **aposd-designing-deep-modules** | Interface design, design-it-twice |
| **aposd-simplifying-complexity** | Error reduction, pull-down technique |
| **aposd-improving-code-clarity** | Comments-first, naming |
| **aposd-maintaining-design-quality** | Strategic vs tactical mindset |
| **aposd-reviewing-module-design** | Complexity symptoms detection |
| **aposd-verifying-correctness** | Pre-commit verification |

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
