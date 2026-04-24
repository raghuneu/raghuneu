# Hi, I'm Raghu Ram 👋

**AI Engineer** · MS Information Systems @ Northeastern University (GPA: 4.0) · Boston, MA

I build AI systems that work in production — multi-agent pipelines, RAG architectures, and agentic backends. Previously 5+ years as a Senior Software Engineer at CitiusTech (GE Healthcare) and Infosys (Goldman Sachs). Now focused on applied AI/ML engineering.

---

## 🔭 What I'm Building

### [FinSage](https://github.com/raghuneu/finsage) — Multi-Agent Financial Intelligence Platform
End-to-end pipeline that generates 15–20 page financial research reports from a ticker symbol using a 4-agent LangChain orchestration system, Medallion data architecture (Snowflake, dbt, Airflow, AWS S3), and iterative VLM chart refinement.
- RAG pipeline over SEC filings with inline source citations
- Cut pipeline runtime from 35 → 16 min via Airflow parallelization and incremental dbt models
- VLM critique-history loop preventing contradictory chart revisions

### Agentic Document Generation Pipeline
Fully local AI pipeline on macOS M1 — a browser extension captures structured content from any webpage, a 3-pass Chain-of-Thought LLM transforms it into a polished document, and a FastAPI/Redis backend compiles and delivers a PDF — all with zero cloud dependency.
- Improved output quality score from 45 → 71/100 across 7 prompt engineering iterations using failure-driven eval methodology
- Zero hallucination in critical document sections via modular LaTeX architecture — a structural constraint, not a prompting workaround
- Self-profiling pipeline recording 12+ per-run metrics (tokens/sec, RAM delta, generation time) enabling data-driven model evaluation

### [PhotoMind](https://github.com/raghuneu/photomind) — Multimodal Photo Knowledge Base
RAG system with dual-index retrieval: CLIP semantic embeddings for visual queries + OCR-based text extraction for structured queries, with a rule-based router directing each query type to the right index.
- Eval-first methodology: ground truth corpus defined before any pipeline code
- 5-class silent failure taxonomy with per-class confidence thresholding

---

## 🛠️ Technical Skills

**Languages:** Python · TypeScript · JavaScript · Java · SQL

**AI/ML:** LangChain · LangGraph · PyTorch · Hugging Face · RAG · Agentic Pipelines · OpenAI API · Prompt Engineering · CLIP · Vector Databases (Qdrant)

**Backend:** FastAPI · Node.js · NestJS · Spring Boot · RESTful APIs · Redis · RabbitMQ · Distributed Systems

**Data:** Snowflake · dbt · Apache Airflow · PostgreSQL · AWS S3 · Pandas · NumPy · ETL

**Cloud & DevOps:** AWS (Lambda, SQS, S3) · Docker · Jenkins · CI/CD · Git

**Frontend:** React · Next.js · Angular · Redux

---

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=raghuneu&show_icons=true&theme=default&hide_border=true&count_private=true" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=raghuneu&layout=compact&theme=default&hide_border=true&langs_count=6" height="150" alt="Top Languages" />
</p>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=raghuneu&theme=default&hide_border=true" height="150" alt="GitHub Streak" />

---

## 🎓 Background

- **MS Information Systems** — Northeastern University, Boston (2025–2027) · GPA: 4.0
  - Coursework: Machine Learning & Deep Learning · Generative AI & LLMs · Data Engineering
- **Senior Software Engineer** — CitiusTech (GE Healthcare) · 2022–2025
  - Built 12-lead ECG signal processing module from scratch; led FDA submission compliance across 3 product releases
- **Systems Engineer** — Infosys (Goldman Sachs) · 2019–2022

---

## 🔍 Currently Looking For

**AI Engineering internships and co-ops** (Summer/Fall 2026) and **full-time AI/ML Engineer roles** starting Summer 2027.

I'm especially interested in teams building with agentic systems, multi-modal pipelines, or production-grade LLM infrastructure. Open to both research-adjacent and applied engineering roles.

📬 [shantharajamani.r@northeastern.edu](mailto:shantharajamani.r@northeastern.edu) · [LinkedIn](https://linkedin.com/in/srraghuram)

---

## ⚡ A Few Things About Me

- I've shipped production code for GE Healthcare's clinical devices — I think carefully about what happens when models are wrong
- My day-one instinct on a new ML system is to write the eval before the model
- I once debugged a race condition that was blocking an FDA submission — found it by manually reproducing a flaky async failure no one else could trigger consistently
- Currently reading: anything about systems that fail gracefully

---

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=raghuneu&style=flat-square&color=grey" alt="Profile views" />
</p>
