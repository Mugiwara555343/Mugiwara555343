

# Mauricio A. Ventura

**AI Systems Engineer (RAG · Python · Docker · Qdrant · LLMs)**  
Local-first LLM architecture · Retrieval systems · Offline AI tooling

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/mauricio-ventura-52a14425a)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/Mugiwara555343)
[![3D Portfolio](https://img.shields.io/badge/Portfolio-3D%20Art-red?logo=google-drive)](https://drive.google.com/drive/folders/1dkPJfTs0yhIqHl96e7kushHLTKjZIwOc)



### 👋 About me

Self-taught AI Systems Engineer building **local-first RAG pipelines**, vector search, and LLM-backed applications on top of Python, Docker, Qdrant, and Ollama.

I design end-to-end systems that:

- Ingest messy local files (TXT, MD, PDF, CSV, HTML, DOCX, images, audio)
- Normalize them into structured JSON / JSONL
- Generate embeddings and index them in a vector database (Qdrant)
- Expose semantic search and “ask” workflows via APIs and a simple web UI
- Run fully offline on consumer hardware

My background in operations and support sharpened my instincts for reliability, documentation, workflow design, and fast troubleshooting. I care about **reproducibility, observability, and clear architecture**, not just demos.

I’m currently looking for roles as an **AI Systems / RAG Engineer** or **AI Automation / Integrations Engineer**.

---

### 🧠 What I build

- **Local-first AI memory systems** – RAG pipelines that don’t depend on the cloud
- **Dropzone → JSONL ingestion tools** – deterministic, idempotent, schema-validated
- **Vector-backed search** – Qdrant-based semantic retrieval for personal or team knowledge
- **LLM-backed APIs & workers** – FastAPI services, workers, and health/smoke checks
- **Developer-facing tools** – prompt libraries, token-efficient flows, and automations

---

### 🚀 Core projects

#### 🔹 [jsonify2ai](https://github.com/Mugiwara555343/jsonify2ai)
Local-first AI memory / RAG system.

- Multi-format ingestion: TXT/MD/PDF/CSV/HTML/DOCX/IMG/AUDIO → normalized JSONL
- Embeddings stored in **Qdrant** for semantic search and filtered retrieval
- **Dockerized stack**: API, worker, Qdrant, web UI
- Health endpoints + **smoke scripts** to verify vector points, API/worker liveness, and exports
- Optional LLM synthesis via **Ollama** (fully offline)

> _Goal: a universal “throw-anything-at-it” ingestion + retrieval engine for local AI systems._

---

#### 🔹 [note2json](https://github.com/Mugiwara555343/note-to-json-demo)
Real-time Markdown/TXT watcher → JSON.

- Converts notes to JSON in sub-second time
- Schema-validated via `jsonschema`
- Deterministic IDs for idempotent re-runs
- Designed as the ingestion spine for larger memory/RAG systems

---

#### 🔹 [cursor-coding-agent-os (fork)](https://github.com/Mugiwara555343/cursor-coding-agent-os)
Prompt and flow rework for a local-first coding agent.

- Re-engineered prompt library and flows
- Cut average token usage by ≈60% on low-VRAM local models
- Focus on cost control, determinism, and better behavior for constrained hardware

---

### 🧰 Tech stack

**AI / RAG / LLM**
- RAG pipelines · embeddings · vector search · semantic retrieval  
- Large Language Models (LLM) · local model orchestration (Ollama)  
- Prompt engineering · text generation

**Backend / Infra**
- Python · FastAPI  
- Docker · Docker Compose  
- Qdrant · JSON / JSONL  
- Bash / Shell scripting · Git  
- Linux & Windows environments

**Dev tools**
- VS Code · Open WebUI · LM Studio  
- Markdown · basic TypeScript/React for UI wiring

---

### 🎯 What I’m looking for

I’m actively open to:

- **AI Systems Engineer / RAG Engineer** roles  
- **AI Automation / Integrations Engineer** roles  
- Early-stage teams building local-first AI tools, internal copilots, or retrieval systems

If you’re working on AI systems, local-first tooling, or retrieval-heavy products and want someone who has already built full pipelines end-to-end, feel free to reach out.

---

**Reach out:** [LinkedIn](https://linkedin.com/in/mauricio-ventura-52a14425a) | [Portfolio](https://drive.google.com/drive/folders/1dkPJfTs0yhIqHl96e7kushHLTKjZIwOc)

---

> *Building AI that remembers, runs offline, and scales locally.*
