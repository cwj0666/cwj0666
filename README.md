![Wonjun Choi — Data & AI Engineer](assets/header.svg)

I design data systems and build AI services, working across backend APIs, data pipelines, retrieval, and model evaluation. I am currently developing **Seorap**, where I lead product planning, backend, data, and model work.

## Selected Projects

### Seorap
**Beauty product and routine manager** · Aug 2026 – present

Seorap lets users register products from photos, compare ingredients and usage feedback, and track changes in their skin.

- Fine-tuned a PP-OCRv5 Korean recognizer on cosmetic package images, raising ingredient recall from **0.84 to 0.91**.
- Merged seven per-region skin grading models into one shared backbone with distillation, reaching **QWK 0.755** on an independent validation set.
- Added source-text verification to LLM batch outputs and blocked **46** mismatched product names before storage.

[Live app](https://seorap-beauty.vercel.app/)

### CMS
**Energy data platform** · May – Jun 2026

CMS collects and aggregates meter events into model inputs for power-demand forecasting and meter anomaly detection. Team project.

- Designed schemas that trace a **15M-row** event ledger through 1-minute, 15-minute, and hourly aggregates to model features.
- Prevented duplicate storage on redelivery by keeping source event keys separate from transport offsets.
- Separated live and backfill consumers so recovery jobs do not delay live ingestion.

### ArXplore
**AI paper search and RAG service** · Mar – Apr 2026

ArXplore provides paper search, source-grounded summaries, and per-paper Q&A. Team project.

- Built hybrid full-text and vector search reaching **Hit@10 0.883** on 111 queries.
- Parallelized both retrieval channels, cutting median search latency from **489 ms to 282 ms**.
- Added grounding rules to the agent prompt, raising the refusal rate on unsupported questions from **73.3% to 93.3%**.

[Repository](https://github.com/cwj0666/ArXplore)

## Tech Stack

**Languages & Backend**

<p>
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/python-dark.svg"><img src="assets/python.svg" alt="" width="20" height="20"></picture>&nbsp; Python &nbsp;&nbsp;
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/sql-dark.svg"><img src="assets/sql.svg" alt="" width="20" height="20"></picture>&nbsp; SQL &nbsp;&nbsp;
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/fastapi-dark.svg"><img src="assets/fastapi.svg" alt="" width="20" height="20"></picture>&nbsp; FastAPI &nbsp;&nbsp;
</p>

**Data**

<p>
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/postgresql-dark.svg"><img src="assets/postgresql.svg" alt="" width="20" height="20"></picture>&nbsp; PostgreSQL &nbsp;&nbsp;
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/apachekafka-dark.svg"><img src="assets/apachekafka.svg" alt="" width="20" height="20"></picture>&nbsp; Apache Kafka &nbsp;&nbsp;
</p>

**AI**

<p>
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/pytorch-dark.svg"><img src="assets/pytorch.svg" alt="" width="20" height="20"></picture>&nbsp; PyTorch &nbsp;&nbsp;
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/langchain-dark.svg"><img src="assets/langchain.svg" alt="" width="20" height="20"></picture>&nbsp; LangChain &nbsp;&nbsp;
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/langgraph-dark.svg"><img src="assets/langgraph.svg" alt="" width="20" height="20"></picture>&nbsp; LangGraph &nbsp;&nbsp;
</p>

**Operations**

<p>
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/docker-dark.svg"><img src="assets/docker.svg" alt="" width="20" height="20"></picture>&nbsp; Docker &nbsp;&nbsp;
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/grafana-dark.svg"><img src="assets/grafana.svg" alt="" width="20" height="20"></picture>&nbsp; Grafana &nbsp;&nbsp;
</p>

---

[cwj0666@gmail.com](mailto:cwj0666@gmail.com)

<sub>Technology icons: Simple Icons and official project logos.</sub>
