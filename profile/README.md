# OpenSWE

Open tooling for software engineering with AI coding agents. Most of it ships as [Agent Skills](https://agentskills.io): plain markdown that runs on Claude Code, Codex, Gemini CLI, Cursor, and any other skills-compatible agent.

## Skills

| Repo | What it does |
|---|---|
| [swe-workflow](https://github.com/OpenSWE/swe-workflow) | The idiomatic engineering workflow, **Idea → PRDs → Issues → ship**, as a chain of small, observable steps. |
| [log-decisions](https://github.com/OpenSWE/log-decisions) | Append-only `DECISIONS.md` journal for the calls a spec didn't settle, with decide / assume / escalate rules. |
| [code-review-ensemble](https://github.com/OpenSWE/code-review-ensemble) | Multi-agent code review: GitHub bots + Claude + Codex + any CLI model, cross-referenced to filter hallucinations. |
| [herdr-advisor](https://github.com/OpenSWE/herdr-advisor) | Pair a [Herdr](https://github.com/herdrdev/herdr) worker with a stronger, read-only advisor model that unblocks it while you're away. |

## Infrastructure

| Repo | What it does |
|---|---|
| [cliproxy-key-routing](https://github.com/OpenSWE/cliproxy-key-routing) | [CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) scheduler plugin (Go) that gives each inbound API key its own fallback order over upstream credentials. |

Each repo's README has its install commands. Website: [openswe.net](https://openswe.net)
