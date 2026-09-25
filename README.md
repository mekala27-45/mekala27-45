# Hi, I'm Ajay Mekala 👋

### AI/ML Engineer · Production ML Platforms · MLOps · Frontier Model Evaluation

I build and operate the machine learning platform behind Walmart's promotion and clearance pricing, and I evaluate frontier models on contract for AI labs. Four years across both: **$7.8M in incremental revenue** from automated SKU selection and markdown optimization, and **200+ golden-solution engineering tasks** with **50+ accepted Terminal-Bench environments** authored for frontier coding benchmarks.

M.S. Data Science, Montclair State University (2026)<br>
Authorized to work in the U.S. without sponsorship<br>
New Jersey, USA

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ajaymekala/)
[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=flat&logo=githubpages&logoColor=white)](https://mekala27-45.github.io)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:mekalaajayk@gmail.com)

---

## What I do now

**AI/ML Engineer at Walmart.** The ML platform behind promotion and clearance pricing, on Azure Databricks, Delta Lake and MLflow, with infrastructure in Terraform. It serves 200,000+ predictions per month. Two systems sit on top of it: PromotionsAI, which automates SKU selection across every customer touchpoint, and ClearanceAI, a markdown optimizer that fuses demand elasticity models with stock age heuristics and lifted sell-through 4.6%.

Most of the work is the part that makes those possible. Dockerized inference, unified MLflow lineage, blue-green releases through Azure Pipelines, an automated A/B testing harness, and the reusable connector libraries the team builds on. Research to production lead time down 40%, experiment turnaround down 60%, incident MTTR halved.

**Frontier model evaluation, on contract since 2022** for Handshake AI, Snorkel AI, Mercor and Outlier. Agent trajectory scoring, benchmark task authoring, rubric design, red-teaming. 3,000+ side-by-side preference comparisons at 98%+ agreement with senior reviewers.

---

## Featured Projects

| Project | What it does | Stack |
|---|---|---|
| **[rounds](https://github.com/mekala27-45/rounds)** · ▶️ **[live demo](https://rounds-health-system.mekalaa1.chatgpt.site)** | Healthcare analytics across 12 departments and 2,000 synthetic patients, with reproducible measures, browser SQL, FHIR/CSV reconciliation, and audited patient workflows. Model cards show temporal evaluation, calibration, subgroup results, and failed promotion gates. Synthetic-data demonstration; not for clinical use. | `Python` `DuckDB` `React` `TypeScript` `Cloudflare D1` |
| **[frontdesk](https://github.com/mekala27-45/frontdesk)** · **[evidence explorer](https://mekala27-45.github.io/frontdesk/)** | WhatsApp clinic booking agent with atomic PostgreSQL scheduling, durable webhook processing, and auditable safety tools. Public explorer includes measured concurrency results, searchable scenarios, and step-by-step tool-call replays. Fictional clinic, recorded test evidence. | `Python` `FastAPI` `PostgreSQL` `Next.js` |
| **[trajectory](https://github.com/mekala27-45/trajectory)** · ▶️ **[live demo](https://mekala27-45.github.io/trajectory/)** | Evaluation harness for coding agents that scores the trajectory, not just the outcome. 12 containerized tasks with hidden tests the agent never sees, 10 trajectory metrics, a 10 mode failure taxonomy, and a leaderboard where any run replays step by step. Three agents tied at exactly 100% pass rate and were separated on three other metrics. Six failure modes fired 213 times on runs that **passed** every hidden test, across 68% of all successes, which a conventional failure table reports as zero. 719 tests, 86.7% coverage, every published figure recomputed from the run records by CI. Apache 2.0, `v0.1.1`. | `Python` `Docker` `FastAPI` `Postgres` `Next.js` |
| **[pricepoint](https://github.com/mekala27-45/pricepoint)** | Price elasticity and constrained markdown decisions on public retail data, with temporal evaluation, model gates, shadow serving and drift monitoring. | `Python` `MLOps` |
| **[IntentSentinel](https://github.com/mekala27-45/intent-sentinel)** · ▶️ **[live](https://huggingface.co/spaces/mekalaajayk/intent-sentinel)** | End-to-end ML and MLOps: purchase-intent prediction (LightGBM) with MLflow registry, FastAPI serving, and from-scratch drift detection. The model degrades 0.96 to 0.84 ROC-AUC on unseen holiday traffic and the monitor explains why. | `MLflow` `FastAPI` `Docker` |
| **[GroundedRAG](https://github.com/mekala27-45/grounded-rag)** · ▶️ **[live](https://huggingface.co/spaces/mekalaajayk/grounded-rag)** | Hybrid dense and BM25 RAG over scientific abstracts, evaluated on SciFact's official qrels (nDCG@10 0.72); refuses on weak evidence and flags hallucinated citations. | `Qdrant` `BM25` `RAG` |
| **[NanoGPT-Lab](https://github.com/mekala27-45/nanogpt-lab)** · ▶️ **[live](https://huggingface.co/spaces/mekalaajayk/nanogpt-lab)** | A Llama-style transformer built from scratch (RoPE, RMSNorm, SwiGLU, KV-cache) with ablations and a test proving KV-cache decoding is bit-identical to a full forward pass. | `PyTorch` `Transformers` |
| **[EdgeVision](https://github.com/mekala27-45/edge-vision)** · ▶️ **[live](https://mekala27-45.github.io/edge-vision/)** | Real ImageNet classification 100% in-browser via ONNX Runtime Web (WASM); MobileNetV2 quantized to INT8, 3.6x smaller and 2.15x faster at 90% agreement. | `ONNX` `React` `TypeScript` |
| **[MetricFlow Analytics](https://github.com/mekala27-45/metricflow-analytics)** | End-to-end analytics-engineering platform: 34 dbt models, 5 ML models (XGBoost 89% AUC), Evidence.dev dashboards over a simulated 50K-user SaaS. | `dbt` `Python` `SQL` |
| **[spec-exact-c](https://github.com/mekala27-45/spec-exact-c)** | From-scratch, byte-exact C reimplementations of standard-library algorithms, each verified by a differential fuzzing harness against the reference implementation. | `C` `Testing` `Docker` |
| **[DataLens AI](https://github.com/mekala27-45/datalens-ai)** | Natural-language-to-SQL analytics layer that turns plain questions into queries, charts, and insights. | `Python` `NLP` `SQL` |
| **[DocMind AI](https://github.com/mekala27-45/docmind-ai)** | Document-understanding pipeline that extracts tables, figures, and key-value content from PDFs. | `Python` `CV` `NLP` |
| **[Bioacoustic Platform](https://github.com/mekala27-45/bioacoustic-platform)** | Audio classification platform using signal processing and deep-learning models. | `Python` `PyTorch` `Audio` |

---

## Tech I work with

**Languages** · Python · SQL · TypeScript/JavaScript · Go · Bash · R · C<br>
**ML and Deep Learning** · PyTorch · TensorFlow · scikit-learn · XGBoost · LightGBM · Transformers · RLHF/DPO/SFT · LLM-as-a-judge<br>
**MLOps** · MLflow · Databricks · Docker · Kubernetes · Terraform · FastAPI · blue-green deployment · drift detection<br>
**Data Engineering** · Delta Lake · Spark · PySpark · Airflow · Kafka · dbt · Pandas · NumPy<br>
**Cloud** · Azure (Databricks, Data Lake, Pipelines, Event Hubs) · AWS (S3, Redshift, Lambda) · GCP (BigQuery, Dataflow)<br>
**Databases** · PostgreSQL · Snowflake · BigQuery · MongoDB · Redis · FAISS · pgvector<br>
**Analytics and BI** · Power BI · Tableau · Plotly · A/B testing · hypothesis testing

---

## Let's connect

Open to **AI/ML Engineer, Machine Learning Engineer, MLOps and model evaluation** roles.

📫 **[mekalaajayk@gmail.com](mailto:mekalaajayk@gmail.com)** · 💼 **[LinkedIn](https://www.linkedin.com/in/ajaymekala/)** · 🌐 **[Portfolio](https://mekala27-45.github.io)**
