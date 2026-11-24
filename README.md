# Sabbella Bhagya Sai Anil Reddy

**Backend Engineer | Python · FastAPI · Django · AI Backend Systems**

Backend engineer with 3+ years of experience in Python, Django, Flask and SQL, now focused on AI backend systems. I build backend services, LLM infrastructure and retrieval-augmented generation applications, and I use AI-assisted development workflows while owning architecture, design decisions and validation.

- 💼 **Experience:** Accenture — Analyst, Backend Developer (Internal Tooling); previously Associate Software Engineer, Data Engineer (Banking Project)
- 🧠 **Focus:** LLM integrations, RAG pipelines, hybrid retrieval, MCP and backend engineering
- 🛠️ **Internal tooling:** Built a Flask SQL Validator and packaged it as a reusable AI skill shared with colleagues
- 📍 **Location:** Hyderabad, India
- 🌐 **Portfolio:** [View source](index.html) · [Deploy it on Vercel](DEPLOY.md)
- 💬 **LinkedIn:** [anil-reddy-sabbella9](https://www.linkedin.com/in/anil-reddy-sabbella9/)

## Featured engineering projects

### [LLM Gateway — Unified API for Multiple LLM Providers](https://github.com/anilreddysbs/LLM_Gateway)

An OpenAI-compatible FastAPI gateway routing requests across Gemini and OpenAI-compatible providers through model aliases, with SSE streaming.

- Sliding-window rate limiting using an atomic Redis Lua script.
- Exact-match caching with lock-based cache-stampede protection and per-key monthly budgets.
- Exponential backoff with jitter, a Redis-backed three-state circuit breaker and provider fallback before the first streamed chunk.
- Token/cost tracking with Python Decimal arithmetic, asynchronous batched PostgreSQL usage logging, admin analytics and Prometheus metrics.
- Custom load-test results: cache hits below 5 ms p50 and 100% request success during a simulated primary-provider outage.

**Stack:** Python, FastAPI, Redis, PostgreSQL, Docker, Prometheus.

### [DocuTrace — Multi-PDF RAG Assistant](https://github.com/anilreddysbs/DocuTrace-)

An end-to-end RAG application that answers questions over multiple PDFs while preserving document and page references for retrieved evidence.

- Page-level extraction, recursive chunking, 384-dimensional MiniLM embeddings and persistent ChromaDB storage.
- Hybrid retrieval combines dense search and BM25 using reciprocal rank fusion.
- Evidence is surfaced with document/page references.
- Retrieval evaluation reports Precision@K, Recall@K and MRR on sample DataOps documents, with automated tests.

**Stack:** Python, Streamlit, PyMuPDF, Sentence Transformers, ChromaDB, Gemini.

### Local MCP Server — Job Scheduler for VS Code (Hackathon)

Built a local Model Context Protocol server that lets VS Code and its AI assistant trigger and manage scheduled jobs through tool calls.

## Professional experience

**Accenture — Analyst, Backend Developer (Internal Tooling)**  
*March 2025 – Present · Hyderabad, India*

- Built an internal Flask-based SQL Validator to automate rule-based validation of database change requests and reduce manual SQL review.
- Converted the validator into a reusable AI skill and shared it with colleagues for use in project workflows.
- Use VS Code with AI coding assistants for development, debugging and query work.

**Accenture — Associate Software Engineer, Data Engineer (Banking Project)**  
*July 2023 – February 2025 · Hyderabad, India*

- Maintained Hadoop and Hive ETL pipelines supporting daily large-scale data processing in a banking environment.
- Monitored and resolved 20+ production issues daily through SQL-based validation and debugging.
- Promoted to Analyst within two years.

## Technical skills

| Area | Skills |
| --- | --- |
| **AI / LLM** | LLM API integration (Gemini, OpenAI-compatible), Prompt Engineering, RAG ingestion/chunking/embeddings/hybrid retrieval/generation, MCP, Agent Skills, Precision@K, Recall@K, MRR |
| **Backend** | Python, FastAPI, Django, Django REST Framework, Flask, REST API design, JWT/OAuth2, SSE streaming, asyncio |
| **Data & Storage** | PostgreSQL, MySQL, SQLite, SQLAlchemy, Alembic, Redis, ChromaDB, SQL, Hadoop/Hive ETL |
| **Infrastructure & Tools** | Docker, Docker Compose, AWS (EC2, S3), Prometheus, pytest, Git, Linux, Postman |
| **AI-assisted development** | VS Code, Claude, Codex, OpenCode, Antigravity |

## Education & certification

- **B.Tech, Computer Science and Engineering** — Lakireddy Bali Reddy College of Engineering · CGPA: 8.93 / 10
- **Claude Certified Associate — Foundations**, Anthropic · Issued November 2026 · Valid until November 2027

## Achievements

- Promoted to Analyst within two years at Accenture.
- Solved 100+ coding problems on HackerRank and LeetCode.

## Connect

- **Email:** [anil.reddy.sbs@gmail.com](mailto:anil.reddy.sbs@gmail.com)
- **LinkedIn:** [linkedin.com/in/anil-reddy-sabbella9](https://www.linkedin.com/in/anil-reddy-sabbella9/)
- **GitHub:** [github.com/anilreddysbs](https://github.com/anilreddysbs)

---

*This profile and the portfolio are aligned to my latest resume. Project implementation details and measured results are described at the linked repositories.*