# Hi, I'm Sneha 👋

**Portfolio:** [snehamondal-data.github.io](https://snehamondal-data.github.io)

**Data engineer.** For three years I was the only data engineer at a six-brand DTC commerce group, which meant I built the platform rather than operated one someone else chose: the ingestion, the warehouse, the models, the quality checks and the documentation.

I like the unglamorous half of this job. The rerun that doesn't double-count, the alert that fires before anyone sees a wrong number, the bill that stops growing.

### What I work with

**Languages** &nbsp;Python · SQL · TypeScript

**Warehouse & modeling** &nbsp;BigQuery · PostgreSQL · Dataform · dbt · dimensional modeling, SCD Type 2, documented grain

**Pipelines** &nbsp;Event-driven and batch ETL on GCP (Pub/Sub, Eventarc, Cloud Run, Cloud Functions, Cloud Tasks) · REST & GraphQL ingestion · retries, idempotent replay, checkpointed backfills

**Reliability** &nbsp;Data contracts, reconciliation against source, freshness and row-count alerting, pytest, CI/CD

**BI** &nbsp;Looker · Tableau · Power BI

### A few things I've built

- Traced an **$8,000/month** cloud bill that had nothing erroring, just quietly costing money, down to a runaway Eventarc to Cloud Run feedback loop. Fixed it architecturally. **$300/month**, and it stayed there.
- Cut operational data errors **95%** across **43K+ SKUs** by making failures loud instead of silent.
- Built the demand forecast the buying team committed **six months** of purchasing against, then checked it against actual sell-through and corrected where it drifted.

### What I'm building now

🔭 **[marketing-data-reliability-pipeline](https://github.com/snehamondal-data/marketing-data-reliability-pipeline)** — incremental ingestion from a rate-limited API where a rerun inserts *zero* rows, into multi-tenant dbt marts with 84 tests per tenant. An LLM agent sits on top with parsed SELECT-only guardrails and a scored eval harness, because an agent that can reach your data should be tested like any other transformation. Writing the ground-truth answers is what caught a model whose grain was missing $347 of real sales. The eval found it, not a user.

🌱 Going deeper on orchestration and retrieval-augmented systems.

💬 **Open to data engineering roles.** Reach me at [sm6503@rit.edu](mailto:sm6503@rit.edu) or on [LinkedIn](https://www.linkedin.com/in/sneha-mondal23/).

---

*M.S. Data Science, Rochester Institute of Technology · B.S. (Honors) Mathematics, University of Calcutta*
