# Abishek M

I deliver production AI systems: voice agents connected to business data, document-processing services and personal software for retrieval and operational workflows.

Based in Chennai. My official role at cluBITS Solutions is **Graduate Engineering Trainee (GET)**, with an **Applied AI engineering** focus, since August 2025. I joined as a full-stack intern on 23 January 2025 and transitioned in August 2025.

## Delivered work

- **Voice agents:** designed 15 ElevenLabs agents across two workspaces for candidate interviews, dental appointments and insurance verification.
- **SQL-backed MCP integrations:** implemented most of an 11-tool MCP-over-SSE server on Azure App Service, connecting agents to patient, appointment, availability and eligibility data.
- **Real-time voice prototyping:** built a local Azure Voice Live API (GPT Realtime) gateway with a browser client and a telephony-codec transport adapter, wired to a stdio MCP tool server; verified sub-100ms barge-in playback purge and live tool round-trips end to end.
- **Post-call AI reporting:** built an ElevenLabs skill-coach agent and a Claude Sonnet (Azure AI Foundry) scoring pipeline that renders a 14-metric, 3-mode interactive report through a deterministic template engine, not model-generated HTML.
- **Document translation:** delivered PDF, DOCX, XLSX and PPTX translation through Dockerized FastAPI pipelines with caching, cost tracking and recovery; ran a zero-diff production database migration (19 tables, 45 stored procedures) ahead of cutover; developed a priced commercial proposal.
- **Reliability and debugging:** investigated agent failures using Phoenix traces and 474 conversations, closed a SQL-injection bypass, contributed to multi-provider LLM failover, and audited 105 queries across 22 ATS controllers for multi-tenant RBAC, cutting an employee-lookup query from a 15-second timeout to 758ms.
- **Full-stack delivery:** internal HR workflows, ATS features and concurrent part-time freelance talent-marketplace work.

## Selected systems

| System | What it delivers | Evidence |
| --- | --- | --- |
| Azure Voice Live + MCP | Real-time voice gateway on Azure's Voice Live API (GPT Realtime), wired to a stdio MCP tool server. | [Case study](https://tentaciopro.github.io/portfoliov2/work/voice-live-mcp/) |
| Post-call analytics | Post-call audio scored by Claude Sonnet on Azure AI Foundry, rendered through a deterministic template engine. | [Case study](https://tentaciopro.github.io/portfoliov2/work/post-call-analytics/) |
| Reel-finder | Canonical ingestion, deduplication, SQLite FTS5, multilingual embeddings and reciprocal-rank fusion for saved-content search. | [Case study](https://tentaciopro.github.io/portfoliov2/work/reel-finder/) |
| Local-first ledger | Staging, reconciliation, saved review decisions, undo and backup/restore in a local application. | [Case study](https://tentaciopro.github.io/portfoliov2/work/local-ledger/) |
| SafeSupport | Retrieval-grounded support triage, response drafting, escalation rules and an evaluation harness. | [Source](https://github.com/TentacioPro/SafeSupport) |
| AgenticLoop | A spec-driven operational workflow for coding agents, evolved from published practices. | [Source](https://github.com/TentacioPro/AgenticLoop) |

Professional and personal systems are production work. Case studies describe their scope, contribution boundaries, verification and remaining work; production status does not imply public SaaS scale or completed model-quality evaluation. Private data and source remain private.

I direct coding-agent implementation, review changes, debug integrations and verify delivered behavior. Upstream tools and forks retain their original authorship.

**AI and integrations:** ElevenLabs, MCP, LangGraph, LangChain, LLM APIs and Arize Phoenix.  
**Engineering:** Python, JavaScript/TypeScript, SQL, FastAPI, React, Node.js, MongoDB, Redis, Docker and Azure.  
**Delivery workflow:** Claude Code, Codex, scoped context, code review and runtime verification.

Seeking Applied AI, GenAI, voice-agent, integration and suitable implementation/FDE opportunities in Tamil Nadu, Bengaluru, Hyderabad or India-remote teams with suitable IST hours.

[Portfolio](https://tentaciopro.github.io/portfoliov2/) · [LinkedIn](https://www.linkedin.com/in/abishek-maharajan/) · abishekmdev@gmail.com
