<div align="center">

# celladore

**AI developer tooling — agent orchestration, cost operations, and the infrastructure that runs them.**

</div>

## What we build

celladore is the home of **[Retort](https://github.com/celladore/retort)**, a Windows-first, polyglot framework for orchestrating teams of AI coding agents — agent teams, skills, quality gates, and governance for real projects — plus the supporting stack that keeps it observable and affordable to run.

## Public projects

| Project | What it does |
|---|---|
| [**retort**](https://github.com/celladore/retort) | Core agent-orchestration framework — agent teams, skills, quality gates, and governance |
| [**codeflow-engine**](https://github.com/celladore/codeflow-engine) | Multi-agent AutoPR engine — automated PR generation, code review, and DevOps workflows |
| [**tokenutil**](https://github.com/celladore/tokenutil) | Token counting and document-chunking primitives for LLM workloads |

## Supporting stack

Retort and codeflow-engine (above) are backed by a handful of private repos — described here for context, not linked, since they're private and a link would just 404 for most visitors:

- **baton** — the shared task graph agents and humans both read/write: a Kanban UI plus an MCP server, so multi-agent work stays coordinated instead of duplicated.
- **sluice** — the OpenAI-compatible AI gateway every model call in the stack routes through (LiteLLM-routed, deployed on Azure Container Apps).
- **docket** — tracks what the rest of the stack costs: LLM spend, usage analytics, and cost optimisation.
- **deck** — a desktop tray/CLI tool for day-to-day ops across the stack.

## Get involved

Found a bug or have an idea? Open an issue on the relevant repo — our [contribution guide](https://github.com/celladore/.github/blob/main/CONTRIBUTING.md) and issue templates apply org-wide.

Found a security issue? Please see our [security policy](https://github.com/celladore/.github/blob/main/SECURITY.md) rather than filing a public issue.
