## Hi there, I’m Ragha and welcome to my portfolio 👋

Data professional focused on buulding reliable analytics systems, BI reporting layers, and experimentation workflows.

I design end-to-end workflows that move from raw data to structured modeling, statistical 
analysis, and stakeholder-ready dashboards — across both on-prem and cloud data warehouses.

- Python (EDA, data validation, data cleaning reusable modules)
- Analytics engineering (Snowflake, PostgreSQL, SQL views & materialized views)
- dbt modeling (staging → intermediate → marts, testing, lineage, incremental models)
- BI dashboards built on strong semantic layers (Power BI, DAX, & DirectQuery)
- Experimentation workflows (A/B tsting, guardrails, decision thresholds)
- End-to-end ownership: ingestion → modeling → analytics → dashboards
- Git based documentation & version control

## How I work

- Prefer database-first transformations, choosing ETL or ELT based on data scale.
- Treat analytics like software: versioning, testing, and reproducibility matter.  
- Optimize for clarity, performance, and trust.
- Build systems that are explainable, maintainable and scalable.


## Featured Projects

### 🛒 Retail Analytics Engineering Pipeline (Instacart)
Production-style PostgreSQL analytics warehouse (3M+ rows) with a SQL semantic layer and live 
Power BI dashboards via DirectQuery.

#### Techstack: Python · PostgreSQL · Power BI · dbt

- Core KPIs implemented directly in SQL views and materialized views
- Performance optimiyed via indexing and pre-aggregation
- DirectQuery dashboards consuming database-layer metrics
- dbt used to replicated modeling layers and generate lineage documentation

🔗 Repo: https://github.com/raghalink/Retail_Analytics_Engineering_Pipeline

---

### 🚀 Incrementality Lab – Growth Experimentation

Simulates how a product or growth team evaluates whether an A/B test should be rolled out.
Built a structured experimentation workflow with validity checks, guardrails, and practical impact thresholds to support real deployment decisions.

#### Techstack: Snowflake · dbt · Snowpark Python · Power BI

* Modeled experiment population and KPIs in dbt
* Implemented rollout decision logic with confidence thresholds
* Added guardrail protection for engagement metrics
* Built a two-page dashboard for decision and segment analysis

🔗 Repo: [https://github.com/raghalink/Incrementality-Lab](https://github.com/raghalink/Incrementality-Lab)

---

### 📊 Rossmann Analytics Engineering (dbt)
End-to-end analytics workflow from raw ingestion throuhg deterministic cleaning and layered warehouse modeling.

#### Techstack: Python · dbt · PostgreSQL · Power BI.

- Deterministic ETL in Python with validation checks
- dbt layered modeling (staging -> intermediate -> marts)
- Business tests and lineage documentation
- Power BI dashboards built on curated dbt marts

🔗 Repo: https://github.com/raghalink/dbt_rossmann_anayltics

---

### ❄️ Marketing Analytics Engineering Pipeline 
End-to-end, Cloud-native marketing analytics workflow focused on incremental processing, clean modeling, and attribution-aware modeling.

#### Tech: Python · Snowflake · dbt · Power BI

- Incremental ingestion into Snowflake (ELT)
- Python used for EDA, sanity checks, and batch preparation (no business logic)
- dbt models produce BI-ready daily marts (campaign and overall performance)
- Incremental correctness validated via SQL tests (no duplicates, append behavior)
- Power BI dashboard built directly on dbt marts with a thin semantic layer

🔗 Repo: https://github.com/raghalink/Marketing_Analytics_Engineering_Pipeline

📍 Berlin, Germany  
🧠 Open to Analytics Engineer / BI / Data Analyst roles / Product Analytics roles  
🔗 LinkedIn: <https://www.linkedin.com/in/raghavendraprasad9/>

