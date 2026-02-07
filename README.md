# Fatima Farman — Analytics Engineer | Product nalytics + FinTech (dbt + BigQuery + Airflow)

I own analytics domains end-to-end (**modeling → QA → orchestration → BI**) that transform **HRIS + ATS + transaction data** into **tested marts + executive dashboards** using **dbt + BigQuery + Airflow + CI**.  

Supports hiring leaders with **stage conversion, drop-offs, bottlenecks, and funnel performance trends** in a single executive view. Built production-grade **BNPL payment analytics** processing $9.1M GMV with 60 automated quality tests.

**Open to:** Analytics Engineer (People domain / FinTech) • People Data Analyst • Payments Analytics  
🌍 Remote / UAE / KSA / Europe | 📍 Karachi, Pakistan  
📧 fatimafarman0@gmail.com · LinkedIn: https://www.linkedin.com/in/fatima-farman

---

## Proof (receipts, not claims)

### People Analytics Domain
- ✅ **dbt tests + QA automation:** `python qa/run_qa.py` → `qa/reports/qa_report.md`  
  Latest run: **PASS = 13** tests in the People Analytics domain.  
  Proof: `proof/dbt_test_pass_13.png`
- ✅ **Airflow orchestration:** daily dbt pipeline via `dbt_people_analytics_daily` DAG  
  Proof: `proof/airflow_dag_success.png`
- ✅ **Marts delivered:**  
  `dim_employee`, `fct_hiring_funnel`, `fct_hiring_funnel_incremental`  
  Contracts + tests: `domains/people_analytics/models/marts/schema.yml`
- ✅ **Executive dashboard:** Hiring Funnel Overview (Looker Studio)  
  Proof: `proof/looker_funnel_dashboard.png`

### FinTech BNPL Analytics
- ✅ **Production-grade dbt models:** 12 models (staging → intermediate → marts)  
  **PASS = 60** automated tests with 0 errors  
  Proof: `docs/images/test_results.png`
- ✅ **Full data lineage:** Interactive documentation with DAG visualization  
  Proof: `docs/images/lineage_graph.png`
- ✅ **Incremental processing:** Partitioned by date, clustered by merchant/customer  
  Proof: `docs/images/model_details.png`
- ✅ **Business metrics:** $9.1M GMV, 50K transactions, 77.3% BNPL adoption  
  Repo: https://github.com/FATIMA-FARMAN/fintech-bnpl-analytics

---

## Featured projects

### 1) FinTech BNPL Analytics Platform
**dbt · DuckDB · Airflow · SQL · Data Quality**

Production-grade Buy Now Pay Later analytics domain modeling Tabby's payment infrastructure. Processes $9.1M GMV across 50,000 transactions with comprehensive testing and monitoring.

**Technical Highlights:**
- 12 dbt models: 4 staging → 3 intermediate → 5 marts (facts + dimensions)
- 60 automated data quality tests (100% pass rate)
- Incremental materialization with partitioning by date, clustering by merchant/customer
- Full data lineage documentation with interactive DAG
- Airflow orchestration with daily 2 AM UTC runs

**Business Value:**
- Merchant performance tracking (GMV, capture rate, fraud rate by tier)
- Customer risk scoring (on-time payment rate 93.7%, default rate 0.4%)
- BNPL portfolio health monitoring (77.3% adoption rate)
- Repayment analytics across 141K installments

**Proof:**
- Repo: https://github.com/FATIMA-FARMAN/fintech-bnpl-analytics
- Test results: 60 PASS, 0 ERROR (`docs/images/test_results.png`)
- Full lineage graph (`docs/images/lineage_graph.png`)
- Model documentation (`docs/images/model_details.png`)
- README with architecture diagram & sample queries

---
### 2) SuperApp Customer Lifecycle Analytics Platform (BNPL + Loyalty + Engagement)
**dbt · DuckDB · Airflow · SQL · Product Analytics**

End-to-end **customer lifecycle analytics platform** for a simulated **FinTech SuperApp** integrating **BNPL, engagement, and loyalty**. Built to mirror **Tabby-scale product analytics**, enabling activation, retention, reactivation, and loyalty analysis on production-style datasets.

**Technical Highlights**
- Layered dbt project: **staging → intermediate → marts**
- Lifecycle-focused marts:
  - `fct_customer_activation`
  - `fct_customer_retention`
  - `fct_reactivation_events`
  - `fct_loyalty_engagement`
- Incremental models optimized for event-level data
- DuckDB-backed analytics warehouse (fast, portable, reproducible)
- Analytics-ready schemas for **A/B testing & experimentation**
- Airflow orchestration for repeatable lifecycle pipelines

**Business & Product Analytics**
- Activation funnel analysis (signup → first BNPL → repeat usage)
- Retention & cohort tracking (D7 / D30 behavior)
- Reactivation patterns after inactivity
- Loyalty engagement signals tied to repeat GMV
- Cross-product usage analysis inside a SuperApp ecosystem

**Why this project matters**
- Demonstrates **Product Analytics + Analytics Engineering** ownership
- Extends beyond payments into **customer behavior & growth**
- Directly aligned with **SuperApp / BNPL / FinTech product teams**

**Proof**
- Repo: https://github.com/FATIMA-FARMAN/superapp-lifecycle-analytics  
- README includes lifecycle metrics, dbt models, and business framing
----

### 3) Analytics Domain Ownership — People Analytics (Flagship)
**dbt · BigQuery · Airflow · CI · Data Contracts**

End-to-end People Analytics domain with staging → intermediate → marts, contracts/tests, orchestration, QA runner, and an executive hiring funnel dashboard.

- Repo: https://github.com/FATIMA-FARMAN/analytics-domain-ownership  
- Proof artifacts:
  - `qa/reports/qa_report.md` (**PASS = 13**)  
  - Incremental model: `fct_hiring_funnel_incremental`  
  - `proof/airflow_dag_success.png`  
  - `proof/looker_funnel_dashboard.png`

---

### 4) People Analytics DWH + Executive Dashboard
**BigQuery · dbt · Looker Studio**

People Analytics warehouse for **headcount, hiring funnel, and attrition**, modeled into BI-ready marts and surfaced in an executive dashboard.

- Repo: https://github.com/FATIMA-FARMAN/people_analytics_dwh  
- Proof:
  - Warehouse schema / marts overview
  - Executive dashboard link (hiring funnel + headcount + attrition)

---

### 5) Fraud Detection Pipeline (FinTech Risk)
**Python · SQL · ML · Reporting**

Fraud detection prototype on transaction data: feature engineering, model training, evaluation, and risk reporting.

- Repo: https://github.com/FATIMA-FARMAN/fraud-detection-project  
- Proof:
  - Jupyter notebook with full pipeline
  - Model performance summary (metrics + confusion matrix)
  - Short report (Markdown or PDF)

---

## Stack

**Core:** SQL (BigQuery) · dbt · Airflow · Python · GitHub Actions  
**Databases:** BigQuery · DuckDB · PostgreSQL  
**BI:** Looker Studio · Tableau  
**Testing:** dbt_utils · dbt_expectations · Great Expectations  
**Domains:** People Analytics · Payments Analytics · Risk Analytics

---

## Certifications

- **dbt Analytics Engineering** (in progress)
- **Google Cloud Platform:** Data Engineer, Data Analyst
- **University of Pennsylvania:** People Analytics, Customer Analytics, Operations Analytics, Accounting Analytics

---

⭐ **Open to Analytics Engineering roles in People Analytics or FinTech/Payments domains**

📧 For collaboration or opportunities: fatimafarman0@gmail.com




