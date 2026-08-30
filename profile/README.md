<div align="center">

# celladore

**Deterministic AI Infrastructure — Multi-Modal Ingestion, Agent Orchestration, and Sovereign Gateway Telemetry.**

[![Website](https://img.shields.io/badge/website-celladoresystems.com-blue)](https://celladoresystems.com)
[![GitHub Orgs](https://img.shields.io/badge/ecosystem-phoenixvc%20%7C%20neuralliquid%20%7C%20nexamesh-orange)](https://phoenixvc.tech)

</div>

## What We Build

Celladore builds modular, verifiable developer infrastructure designed for autonomous agent fleets and production venture pipelines. Built by [Jurie Smit](https://github.com/justaghost) across 2.5 years of production engineering at [Phoenix VC](https://phoenixvc.tech).

## Public Engines

| Project | What it does | License |
|---|---|---|
| [**retort**](https://github.com/celladore/retort) | Core Windows-first agent-orchestration framework — agent teams, skills, quality gates, and governance | MIT |
| [**Mill**](https://github.com/celladore/mill) · [alpha](https://mill.celladoresystems.com) | Document and media conversion workspace for deterministic local tools and authenticated API transformations. Scoped CLI after registry publication: `npx @celladore/mill --help`; bare `npx mill` is not supported. | Unlicensed |
| [**codeflow-engine**](https://github.com/celladore/codeflow-engine) | Temporal-durable AutoPR engine — automated PR synthesis and multi-agent review crews | MIT |
| [**tokenutil**](https://github.com/celladore/tokenutil) | Token counting and document-chunking primitives for LLM workloads | MIT |

## Supporting Ecosystem Stack

The open-source engines are backed by an integrated microservices suite deployed across Azure Container Apps:

- **[Baton](https://celladoresystems.com/baton)** — The shared task graph and coordination backbone: 3-tier MCP server, bidirectional YAML sync, and cryptographic HMAC-SHA256 task leases preventing subagent collisions.
- **[Sluice](https://celladoresystems.com/sluice)** — Sovereign OpenAI-compatible AI gateway deployed on Azure Container Apps with LiteLLM routing, 99.9% uptime SLA failover, and virtual key isolation.
- **[Docket](https://celladoresystems.com/docket)** — Real-time AI spend telemetry, agent-level token attribution, loop containment, and FinOps budget guardrails.
- **[Deck](https://celladoresystems.com/deck)** — Native desktop control center & operations HUD built with Tauri 2.0, React 19, and a .NET 9 sidecar.

## Venture Ecosystem & Partner Orgs

- **[Phoenix VC](https://github.com/phoenixvc)** ([phoenixvc.tech](https://phoenixvc.tech)) — Venture studio & sovereign AI architecture lab.
- **[NeuralLiquid](https://github.com/neuralliquid)** ([neuralliquid.ai](https://neuralliquid.ai)) — Cognitive Mesh enterprise AI & quantitative intelligence.
- **[Nexamesh](https://github.com/nexamesh)** ([nexamesh.ai](https://nexamesh.ai)) — Counter-UAS defense simulation & autonomous sensor mesh.

## Get Involved

Found a bug or have an idea? Open an issue on the relevant repo — our [contribution guide](https://github.com/celladore/.github/blob/main/CONTRIBUTING.md) and issue templates apply org-wide.

Found a security issue? Please review our [security policy](https://github.com/celladore/.github/blob/main/SECURITY.md) rather than filing a public issue.
