# 👋 Hi, I'm Rishi Dixit

🤖 Agentic AI · ⚙️ Backend Development · ☁️ Cloud Engineering (Azure)
📍 Jaipur, India | 🎓 B.Tech (Hons.) CSE — AI/ML, Manipal University Jaipur
💼 Software Engineering Intern @ Grant Thornton Bharat

---

## 🧠 Who Am I?

I'm a final-year CS (AI/ML) student building **production-oriented AI systems** — tool-calling agents, document-processing pipelines, and backend services on Microsoft Azure.

These days my work lives at the intersection of:

- **Agentic AI** — agents that actually *do* things via API tools, not just chat
- **Backend engineering** — clean, secure REST APIs with FastAPI
- **Cloud** — shipping and running it all on Azure

I like turning messy, manual workflows into reliable automated ones — and I care about the boring parts (auth, fallbacks, observability) that make AI tools survive contact with real users.

---

## 🛠️ Tech Stack

- **Languages:** Python, Java, SQL
- **Agentic AI:** Azure AI Foundry, Tool Calling, MCP Servers, Prompt Engineering, OCR
- **Backend:** FastAPI, REST APIs, JWT / OAuth2, SQLAlchemy, Alembic
- **Cloud & DevOps:** Azure App Service, Azure Functions, Azure Storage, Entra ID, Azure DevOps, GitHub Actions, App Insights, CI/CD
- **Databases & Tools:** PostgreSQL, SQLite, Git, VS Code, Sourcetree
- **Also familiar with:** PyTorch, TensorFlow, Scikit-learn, Pandas, NumPy, LangChain

---

## 📂 Projects I'm Proud Of

### [🤖 VeritusAI — Multi-Agent Company Research & Report Automation](https://github.com/RishiDixit-7404/-VeritusAI)
> *FastAPI · PyMuPDF · SQLite · ChromaDB · Python*
- Multi-agent workflow that turns a company name into a branded Microsoft Word research report by discovering, validating, and ingesting annual reports.
- Fully local, zero-key architecture using SQLite for queuing, ChromaDB for vectors, local sentence-transformers, and a mock LLM by default (with open LLM support).
- Built an event-driven worker system featuring process-wide rate limiting, concurrent section agents, and fallback CSV data injection.
- Engineered a robust SSRF guard with per-hop redirect validation to securely fetch external PDFs and data sources.
### [💡 Lumina — Local-First Multi-Agent RAG Platform](https://github.com/RishiDixit-7404/Lumina)
> *Ollama · Qdrant · FastAPI · React (Vite) · Python*
- Hand-rolled 4-agent pipeline (Planner → Retriever → Analyst → Critic) that answers questions over code and PDFs with hybrid retrieval and per-claim citations.
- Built a terminal-style React trace UI featuring an execution graph, latency waterfall, and token-by-token streaming over WebSockets.
- Fully local execution (Ollama, Qdrant, SQLite) with incremental, deterministic AST-aware reindexing via xxhash64 diffing.
- Developed runtime model management to seamlessly swap or pull Ollama chat and embedding models through the UI without restarting.
### [🛡️ Vettra — Automated Compliance Screening](https://github.com/RishiDixit-7404/Vettra)
> *FastAPI · Playwright · BeautifulSoup · SQLite Queue · Python*
- Tool for analysts to upload ZIPs of background-check PDFs, triggering an async worker that scrapes linked sources and uses an LLM to classify adverse risk.
- Developed a multi-stage scraping fallback chain (Playwright → BeautifulSoup → ScraperAPI) protected by strict SSRF guards.
- Features stateful diffing for reprocessed jobs, generating Excel workbooks that highlight risk additions and removals.
- Implemented robust queue mechanics including job visibility timeouts, automatic retries, and dead-letter routing using SQLite.

### [🔐 DPDP PrivacyOps — Privacy Scanner & Compliance Evidence Platform](https://github.com/RishiDixit-7404/dpdp-privacyops)
> *FastAPI · SQLAlchemy · Alembic · Python*
- PrivacyOps MVP to discover PII across databases, logs, tickets, exports, and AI prompt workflows.
- Metadata-first discovery that flags risky fields, scores confidence, and recommends remediation — no raw data upload needed.
- Modules for scan findings, DSR tracking, consent logging, and DPDP compliance evidence.
- Developed a local Next.js dashboard to visualize findings, trace compliance gaps, and aggregate technical readiness evidence.

<details>
<summary>📈 Earlier ML / fintech projects</summary>

- **Algorithmic Trading System** — FinBERT sentiment analyzer, CUDA-accelerated (<100ms latency), low correlation to SPY
- **Time Series Forecasting** — LSTM for GOOG price prediction with RSI / Bollinger Band features
- **Loan Approval Predictor** — Scikit-learn classifier (~86% accuracy) surfacing credit history as a key signal

</details>

---

## 📜 Certifications

- Microsoft Certified: **Azure AI Engineer / Developer Associate** *(in progress)*
- Microsoft Certified: **Azure Fundamentals (AZ-900)**
- Microsoft: **Artificial Intelligence on Microsoft Azure**
- Oracle Academy: **Database Programming with SQL**

---

## 🧭 What I'm Exploring Now

- Multi-agent and tool-calling patterns on Azure AI Foundry
- MCP servers for connecting agents to real backend systems
- Making AI tools production-safe: evals, guardrails, and observability
- Better prompts = more reliable agents

---

## 💬 Ask Me About

- How I cut manual analyst effort with an agentic background-check tool
- Designing resilient extraction pipelines that don't break on weird sources
- Wiring backend APIs into LLM agents as callable tools
- Running AI workloads on Azure without things falling over

---

## 🤝 Let's Connect

- [LinkedIn](https://www.linkedin.com/in/rishi-dixit-461035279/)
- 📬 rishidixit.7404@icloud.com
- GitHub: you're already here :)

---

> *"Production is just a prototype that survived enough"*
> — Rishi Dixit (probably while debugging an agent at 2AM)
