# Hi, I'm Sneha 👋

**Portfolio:** [snehamondal-data.github.io](https://snehamondal-data.github.io)

**Data engineer.** For 3+ years I was the only data engineer at Veiled Collection, a modest-fashion DTC brand, and then at YNK Incubator, the 3PL behind it, where I built the data platform for six DTC brands: the ingestion, the warehouse, the models, the quality checks and the warehouse tools operations staff worked in.

I love solving complex problems, and I like the unglamorous half of this job: the rerun that doesn't double-count, the alert that fires before anyone sees a wrong number, the bill that stops growing.

### What I work with

**Languages** &nbsp;Python · SQL · TypeScript

**Warehouse & modeling** &nbsp;BigQuery · PostgreSQL · Dataform · dbt · Snowflake · dimensional modeling, SCD Type 2, documented grain

**Pipelines** &nbsp;Event-driven and batch ETL on GCP (Pub/Sub, Eventarc, Cloud Run, Cloud Functions, Cloud Tasks) · REST & GraphQL ingestion · retries, idempotent replay, checkpointed backfills

**Reliability** &nbsp;Data contracts, reconciliation against source, freshness and row-count alerting, pytest, CI/CD

**AI** &nbsp;LLM agents with SQL guardrails and eval harnesses (Anthropic SDK) · fine-tuned BERT · scikit-learn

**BI** &nbsp;Looker · Tableau · Power BI

### A few things I've built

- Modeled a warehouse as data: a grid generator turned the layout into about **8,000** positions in a BigQuery Master Grid, and an installable Apps Script add-on assigned incoming products to them in walking order and updated Shopify.
- Moved those workflows into an operations portal for **six** clients (Vercel, Neon Postgres, Cloud Functions, Cloud Run), on a multi-tenant BigQuery platform with IAM tenant isolation and resumable backfills.
- Cut operational data errors **~95%** across **44K SKUs** with reconciliation against source and daily snapshot checks.
- Traced an **$8,000/month** cloud bill with nothing erroring to a runaway Eventarc to Cloud Run feedback loop. Fixed it architecturally: **$300/month**.

### Projects

🎓 **[racism-in-football-nlp](https://github.com/snehamondal-data/racism-in-football-nlp)**: my M.S. capstone. A hybrid of fine-tuned BERT, an SVM over [CLS] embeddings and a rule layer for coded language: **75.2%** accuracy and **0.68** F1 held-out. The finding I'd lead with: the model was most confident when it was wrong (**0.82** vs **0.69**), so its confidence couldn't be used for routing.

🔭 **[marketing-data-reliability-pipeline](https://github.com/snehamondal-data/marketing-data-reliability-pipeline)**: incremental ingestion where a rerun inserts *zero* rows, multi-tenant dbt marts with **84** tests per tenant, and an LLM agent with parsed SELECT-only guardrails and a scored eval harness. Building the ground-truth SQL for the evals surfaced a mart whose grain missed **$347** of lost sales.

📈 **[fashion-trend-engine](https://github.com/snehamondal-data/fashion-trend-engine)**: does a runway trend travel from luxury to affordable brands? **58** tests, and the data contradicted the hypothesis. The write-up says so.

🌱 Going deeper on orchestration and retrieval-augmented systems.

💬 **Open to AI engineering, data engineering and forward deployed engineering roles.** Reach me at [sm6503@rit.edu](mailto:sm6503@rit.edu) or on [LinkedIn](https://www.linkedin.com/in/sneha-mondal23/).

---

*M.S. Data Science, Rochester Institute of Technology · B.S. (Honors) Mathematics, University of Calcutta*
