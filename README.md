# Hi, I'm Krisha 👋

Software engineer focused on backend, AI/agentic systems, and data engineering. I like owning things end to end, from the API layer down to the data pipeline, and I care about the parts that don't show up in a demo: latency, retries, and knowing why something is slow before I touch it.

MS in Computer Science. Currently building AI-powered products and looking for software, AI, and data engineering roles.

---

## Tech Stack

**Languages:** Python, JavaScript, SQL

**Backend:** FastAPI, Node.js, Django / DRF, GraphQL, REST, JWT auth

**Frontend:** React

**AI / Agentic:** RAG, LangGraph, ChromaDB, Groq Whisper, LLM evals (LLM-as-judge)

**Data Engineering:** ETL pipelines, PySpark, n8n orchestration, time-series partitioning

**Databases:** PostgreSQL, MongoDB, ChromaDB

**Cloud / DevOps:** AWS, Terraform, Azure (AZ-900 certified)

---

## Featured Projects

### 🎙️ [PromptCue](https://github.com/krisha-parikh/PromtCue) — Real-time AI meeting copilot
Built solo, end to end. Live transcription and retrieval-augmented suggestions during a meeting, with sub-2-second streaming latency. The latency win came from profiling the full request path and streaming tokens over the fetch ReadableStream API instead of waiting on the model alone.
**Stack:** FastAPI, React, RAG (ChromaDB), LangGraph, Groq Whisper

### 💬 [Chatify](https://github.com/krisha-parikh/FSD-Chat-App-Mini-Project) — Microservices chat app
Real-time chat serving 1,000+ users, with a 25% latency reduction after refactoring the service boundaries and auth flow.
**Stack:** Node.js microservices, JWT auth, MongoDB, React

### 📊 [DroomScroll](https://github.com/krisha-parikh/Droom-scroll) — YouTube comment analytics pipeline
Batch analytics over YouTube comments, processing ~20K records per batch with orchestrated ingestion and transformation. A Django/DRF variant exists for a separate use case.
**Stack:** FastAPI, PySpark, n8n

### 🌦️ [Weather Data Pipeline](https://github.com/krisha-parikh/Data-pipeline) — AWS ETL
Time-series weather ETL with retry logic and partitioning built in, so the pipeline degrades gracefully instead of dropping data when a source hiccups.
**Stack:** AWS, PostgreSQL, Python

---

## Beyond Code

TED Translator Delegate and TEDNext scholarship recipient. Comfortable explaining technical work to non-technical people and working directly with clients.

---

## Let's Connect

- 📧 kparikh7025@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/kriisha)
- 💻 [GitHub](https://github.com/krisha-parikh)
