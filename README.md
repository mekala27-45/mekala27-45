# Ajay Mekala

I'm an AI/ML engineer at Walmart, where I work on the machine learning platform behind promotion and clearance pricing. Since 2022 I've also done contract model evaluation for Handshake AI, Snorkel AI, Mercor and Outlier: writing benchmark tasks, scoring coding-agent runs and building rubrics.

MS in Data Science, Montclair State University (2026). I live in New Jersey and I'm authorized to work in the U.S. without sponsorship.

[Portfolio](https://mekala27-45.github.io) · [LinkedIn](https://www.linkedin.com/in/ajaymekala/) · [Email](mailto:mekalaajayk@gmail.com)

## At work

The pricing platform runs on Azure Databricks, Delta Lake and MLflow, with the infrastructure in Terraform, and serves more than 200,000 predictions a month. Two systems run on it. PromotionsAI picks the SKUs that go on promotion and has driven $7.8M in incremental revenue. ClearanceAI sets markdown prices from demand elasticity models plus stock-age rules, and it lifted sell-through by 4.6%.

A lot of my time goes into the parts around the models: Dockerized inference, MLflow lineage, blue-green releases through Azure Pipelines, an A/B testing harness, and connector libraries the rest of the team builds on. Research-to-production lead time is down 40%, experiment turnaround is down 60%, and incident MTTR is about half what it was.

The evaluation work adds up to 200+ golden-solution tasks for frontier coding benchmarks, 50+ accepted Terminal-Bench environments, and 3,000+ side-by-side preference comparisons at 98%+ agreement with senior reviewers. It's under NDA, so my public projects are where I use the same ideas on problems I can share.

## Projects

Personal projects on public or synthetic data. None of them use employer code or data.

- [trajectory](https://github.com/mekala27-45/trajectory): scores coding agents on every step of a run instead of only on whether the hidden tests pass at the end. [Leaderboard](https://mekala27-45.github.io/trajectory/)
- [pricepoint](https://github.com/mekala27-45/pricepoint): price elasticity and markdown decisions on the UCI Online Retail II data, with a temporal backtest, promotion gates, shadow serving and drift monitoring. The trailing-mean baseline beat the LightGBM candidate, so the baseline is what it serves. [Demo](https://mekala27-45.github.io/pricepoint/)
- [cityflow](https://github.com/mekala27-45/cityflow): a dbt warehouse for NYC taxi and for-hire trip records, with a dashboard that queries parquet in the browser through DuckDB-WASM. The published figures come from a seeded generator that copies the TLC schema and its data problems. [Dashboard](https://mekala27-45.github.io/cityflow/)
- [frontdesk](https://github.com/mekala27-45/frontdesk): a WhatsApp booking agent for a fictional clinic. Most of the work went into concurrent booking, webhook retries, and refusals that are recorded as tool calls. [Evidence explorer](https://mekala27-45.github.io/frontdesk/)
- [readout](https://github.com/mekala27-45/readout): an A/B testing platform with frozen designs, health checks that run before any metric, and a sequential test checked against simulated null experiments. [Demo](https://mekala27-45.github.io/readout/)
- [groundwork](https://github.com/mekala27-45/groundwork): upload a PDF and ask questions about it. Answers cite their sources, the citations are checked, and there are tests for prompt injection and workspace isolation. [Demo](https://mekala27-45.github.io/groundwork/)
- [northstar](https://github.com/mekala27-45/northstar): analytics on the public Olist e-commerce data, with a dbt warehouse, forecasting, a SQL assistant scored against a test set, and a written memo. [Dashboard](https://mekala27-45.github.io/northstar/)
- [shortlist](https://github.com/mekala27-45/shortlist): the pipeline I use for my own job search. It pulls postings from 16 sources, scores them and pre-fills applications, but it never presses submit.

Older and smaller: [intent-sentinel](https://github.com/mekala27-45/intent-sentinel) (purchase intent model with drift monitoring), [edge-vision](https://github.com/mekala27-45/edge-vision) (INT8 MobileNetV2 running in the browser), [grounded-rag](https://github.com/mekala27-45/grounded-rag) (hybrid retrieval evaluated on SciFact) and [nanogpt-lab](https://github.com/mekala27-45/nanogpt-lab) (a small Llama-style transformer with ablations).

## Tools

- Languages: Python, SQL, TypeScript, Go, Bash
- ML: PyTorch, TensorFlow, scikit-learn, XGBoost, LightGBM, Hugging Face Transformers
- MLOps: MLflow, Weights & Biases, Databricks, Docker, Kubernetes, Terraform, FastAPI
- Data: Spark and PySpark, Delta Lake, Airflow, Kafka, dbt, DuckDB, Postgres
- Cloud: Azure, AWS, GCP

I'm looking for ML engineering, MLOps and model evaluation roles, remote or around New York. Email is the fastest way to reach me.
