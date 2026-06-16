# Akarsh Gajbhiye

Bengaluru, India · [akarshgajbhiye@gmail.com](mailto:akarshgajbhiye@gmail.com) · +91 9589198000
[GitHub](https://github.com/akar5h) · [LinkedIn](https://www.linkedin.com/in/akarsh-gajbhiye/) · [akarshgajbhiye.com](https://akarshgajbhiye.com) · [X](https://x.com/akarshgajbhiye)

AI engineer focused on agent reliability, security, and the infrastructure that lets autonomous agents be trusted with real work. ~6 years building production AI and backend systems. IIT Kanpur, CSE.

---

## Experience

### Kairos — Founder / AI Engineer
*2026 – Present*

- Building an **open-source failure-analysis layer for AI agents**: traces agent runs, clusters them into recurring failure/success patterns, and feeds an eval loop to iterate the agent — detection independent of LLM-as-judge.
- Normalizes heterogeneous agent transcripts (Claude Code, Codex, OpenCode, Paperclip) into a common trace representation. In use with **Blitz** as a design partner.
- Researched **runtime failure detection and intervention** for agents, benchmarked on τ-bench; established the structural limits of runtime correction (the checking layer shares the agent's failure modes), now informing a human-governed control-layer direction.

### AI Security & Red-Teaming Research — Independent
*2026 – Present*

- Implemented **MUZZLE** (adaptive agent red-teaming loop) from scratch, then **generalized it from UI to API surfaces** so it works against tool-using agents.
- Added original research contributions on top: a **rationale layer** (every attack carries a theory of why it should work, scored for accuracy to flag dead attack lines early), **two-level adaptation** (outer bandit selects where, inner technique palette selects how), and **persistent failed-attack memory**.
- Packaged this as **GART**, an autonomous adaptive red-teaming agent — ran fully autonomously against a production-grade HR-screening agent (45 attacks, zero human intervention).
- **Manually red-teamed live production systems** (Moonshot's Kimi, Shortcut AI): infrastructure exploration uncovering exposed endpoints and API keys; responsible disclosure.

### Leadzo — Fractional Head of Engineering
*2026 – Present*

- Own end-to-end engineering delivery for an AI-driven lead-generation product; lead a team of 2 engineers and set technical direction across data, backend, and infrastructure.
- Built the **prospect acquisition pipeline** — scraping, enrichment, and personalized outreach generation — as production systems on AWS.
- Stood up **email infrastructure** (Smartlead) and lifecycle outreach, plus backend services, deployment, and reliability.

### CoreWorks AI — Founding Engineer
*Aug 2025 – Mar 2026*

- Designed and productionized an **agentic document-understanding system using LangGraph**, orchestrating multi-step extraction, validation, and correction; owned model selection, prompting, and cost-vs-accuracy tradeoffs.
- Built a distributed, asynchronous ingestion and enrichment engine for large Excel workbooks (~500K rows) using presigned S3 uploads, Redis-backed workers, and horizontally scalable processing.
- Resolved production OOM/latency failures via early file-shape detection, incremental chunking, and isolation of memory-heavy stages; added checkpoint/stop/resume semantics for long-running workflows.

### Blitz — Senior Software Engineer
*May 2022 – Aug 2025*

- Architected and owned the core backend platform for a high-scale logistics operation — order lifecycle, warehousing, inventory — handling **~1M requests/day**.
- Designed **GeoBlitz**, an in-house agentic system parsing noisy unstructured inputs and orchestrating multi-source retrieval for downstream automation; owned the build-vs-API decision end-to-end.
- Built a **CQRS real-time decision system** (Postgres write model, MongoDB read model) for high-throughput dispatch; integrated Google OR-Tools for constraint-based rider–order ranking.
- Led a team of 2 and contributed to hiring 10+ engineers across the org.

### AppOrchid — Member of Technical Staff, ML/AI
*May 2020 – May 2022*

- Built Python microservices for large-scale legal document ingestion, clause extraction, and semantic analysis in a regulated, auditable domain.
- Developed NLP and computer-vision pipelines (TensorFlow, PyTorch, OpenCV); fine-tuned TableNet for table detection (~88% mAP).

---

## Education

**Indian Institute of Technology, Kanpur** — B.Tech, Computer Science and Engineering

---

## Skills

**Languages:** Python, Go, Java
**AI / ML:** LLM systems, agentic workflows, RAG, evals & observability, AI red-teaming (PyRIT, Garak, Promptfoo), NLP
**Backend:** FastAPI, Django, distributed systems, CQRS, async processing
**Data / Infra:** PostgreSQL/PostGIS, MongoDB, Redis, AWS, Docker, Terraform, OpenTelemetry
