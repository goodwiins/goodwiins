# Abdelghafour El Bikha

**Software engineer building AI applications, backend systems, and developer tools.**  
New York, NY · Open to entry-level software engineering and applied AI roles

[Portfolio](https://www.aelbikha.com) · [LinkedIn](https://www.linkedin.com/in/aelbikha/) · [Goodwiinz organization](https://github.com/Goodwiinz)

I build applications that connect language models to useful workflows: searching research papers, automating browser tasks, and generating educational content. My work spans Python backends, TypeScript interfaces, and Go services.

Through AI/ML and full-stack internships, I've worked on tutoring agents, retrieval pipelines, streaming chat, and React/Flutter applications. I also build and maintain projects under **[Goodwiinz](https://github.com/Goodwiinz)**.

## Featured projects

### [NOUS](https://github.com/Goodwiinz/rag) — Research platform and AI agent
A workspace for searching documents and papers, exploring a knowledge graph, and generating answers with source citations.

- Web and terminal clients share a FastAPI backend.
- LangGraph workflows use PostgreSQL checkpoints and ask for approval before tools write data.
- Agent evaluations check tool actions, database state, answer grounding, and cancellation behavior.

**Python · FastAPI · LangGraph · Next.js · PostgreSQL · Neo4j**  
[Source](https://github.com/Goodwiinz/rag) · [Terminal client](https://github.com/Goodwiinz/nous-cli) · [Project showcase](https://goodwiins.github.io/nous/) · [Evaluations](https://github.com/Goodwiinz/rag/tree/develop/evals)

### [MERIDIAN](https://github.com/goodwiins/computer-use-automation-system/tree/dev) — Browser workflow automation
An LLM discovers workflows in a synthetic banking application and records typed, versioned instructions. Approved workflows replay without further model calls.

- Validates inputs and outputs and rejects ambiguous element matches.
- Supports human handoff and reports failures with evidence.
- Recorded API checks cover account retrieval, missing-member outcomes, and duplicate-request handling.

**TypeScript · Playwright · Zod · Next.js**  
[Source](https://github.com/goodwiins/computer-use-automation-system/tree/dev) · [Recorded evaluation evidence](https://github.com/goodwiins/computer-use-automation-system/blob/dev/docs/meridian/live-evidence.md)

### [Injection-Aware MPNet](https://github.com/goodwiins/prompt-injection-defense) — Prompt-injection detection
A two-stage detector combining contrastively fine-tuned MPNet embeddings with XGBoost. Training includes harmless prompts containing attack-related terms to help distinguish intent from keyword overlap.

The project explores attack detection, false positives, and evaluation across public benchmark datasets. Research manuscript in preparation.

**Python · sentence-transformers · XGBoost**

### [BuildHive](https://github.com/goodwiins/buildhive) — Remote build backend
A Go backend prototype for a self-hosted Docker build platform, with REST APIs, PostgreSQL persistence, bidirectional gRPC forwarding, and builder health reporting.

**Go · PostgreSQL · gRPC · Docker · sqlc**  
In development; the complete build workflow is still being developed.

## Tools I work with

| Area | Technologies |
| --- | --- |
| Languages | Python, TypeScript, Go, SQL |
| Applications | FastAPI, React, Next.js, Flutter |
| AI and retrieval | PyTorch, scikit-learn, sentence-transformers, LangGraph, XGBoost |
| Data | PostgreSQL, Redis, Qdrant, Neo4j |
| Testing and delivery | pytest, Playwright, Vitest, Docker, Kubernetes, GitHub Actions |
| Observability | LangSmith, Prometheus |

## What I focus on

- Making agent actions visible, reviewable, and recoverable.
- Checking application state as well as model responses.
- Building clear APIs and handling timeouts, retries, and partial failures.
- Keeping project claims tied to implementation and recorded evidence.

## Let's connect

I'm looking for **Software Engineer I, backend, and applied AI engineering opportunities** where I can build useful products and grow alongside experienced engineers.

Reach me on [LinkedIn](https://www.linkedin.com/in/aelbikha/) or explore my work at [aelbikha.com](https://www.aelbikha.com).
