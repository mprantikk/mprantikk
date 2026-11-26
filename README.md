<p align="center">
  <img src="assets/hero.svg" alt="Masud Parvej, Lead, Data Ops at Commure. Revenue analytics, automation, and BI." width="100%">
</p>

<p align="center">
  <a href="https://mprantikk.github.io/"><img src="assets/btn-portfolio.svg" alt="Portfolio" height="46"></a>
  &nbsp;
  <a href="https://mprantikk.github.io/resume/"><img src="assets/btn-resume.svg" alt="Resume" height="46"></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/mprantikk"><img src="assets/btn-linkedin.svg" alt="LinkedIn" height="46"></a>
  &nbsp;
  <a href="mailto:mprantikk@gmail.com"><img src="assets/btn-email.svg" alt="Email" height="46"></a>
</p>

## About

I lead data operations at Commure, a healthcare technology company focused on revenue cycle management. When I joined, revenue benchmarking did not exist as a process. I built it from scratch with a small team: the workflows, the QA, the system setup, and the data operations around it. We have since benchmarked revenue for 400+ sites. Today I work across three pods: Revenue Benchmarking, Rev Ops, and Launch QBR.

Before Commure I worked in logistics (Porter), e-commerce and fintech (ShopUp), and FMCG (Grameen Danone Foods). That is 6+ years of turning messy operational data into reports people actually use.

I also build my own tools, like Perfexio, and I write about how to judge AI-generated insights.

- **Based in:** Dhaka, Bangladesh
- **Open to:** remote roles in business intelligence, analytics, and data operations
- **Studying:** M.Sc. in Data Science and Analytics, East West University (expected June 2028)
- **Certified:** Microsoft PL-300, ICAgile ICP-A, CSCA, Google Data Analytics, Data Governance (University of Washington)

## Impact

<p align="center">
  <img src="assets/impact.svg" alt="Impact: 100+ reports and 8+ dashboards at Porter. 98% of QA error-free, 79% less time to benchmark one site, about 60% of manual tasks removed, 40% data management gain, 30% portfolio expansion, 20% productivity gain, 15% HR data accuracy gain." width="100%">
</p>

Benchmarking one site at Commure used to take 24 man hours (three working days). It now takes 5. QA used to be fully manual. A Retool integrity-check failure panel and a Firebase-hosted review panel now handle about 98% of it without errors.

At ShopUp I automated HR reporting end to end: about 30 automated reports that saved 15 hours a week and cut manual effort by 55%, for an HRIS serving 900+ employees. At Porter, key-metric reports went from a couple of hours to under 3 minutes, and sales forecast accuracy rose 30%. At Grameen Danone I was product manager for a Sales App used by 300+ sales reps and 100+ distributors.

## What I work with

<p align="center">
  <img src="assets/toolkit.svg" alt="Toolkit: Power BI, DAX, Tableau, Metabase, Excel VBA, PostgreSQL, SQL Server, Snowflake, Python, Retool, Notion, Linear, data governance, team leadership." width="100%">
</p>

## Selected work

Every project below runs, has tests, and is checked by CI on each push. All data is synthetic.

**Analytics engineering and data quality**

| Project | What it is | Built with |
|---|---|---|
| [**Health Financing Benchmark**](https://github.com/mprantikk/south-asia-health-financing) | Real World Bank data: Bangladesh vs South Asia on who pays for healthcare. Self-refreshing monthly pipeline with a quality gate; Bangladesh has the region's highest out-of-pocket share (79%). | Python, World Bank API, GitHub Actions |
| [**Revenue dbt Warehouse**](https://github.com/mprantikk/revenue-dbt-warehouse) | Layered dbt warehouse (staging → core → finance marts) for healthcare claims, guarded by 52 data tests including a fact-to-mart reconciliation. | dbt, DuckDB, SQL |
| [**Airflow ELT Pipeline**](https://github.com/mprantikk/airflow-elt-pipeline) | Daily, idempotent ELT DAG that lands, cleans and models a claims drop, and fails the run if any data-quality rule breaks. | Airflow, PostgreSQL, Docker |
| [**HR People Analytics**](https://github.com/mprantikk/hr-people-analytics) | HRIS data-quality scoring and safe fixes, attrition and early-attrition analysis, and appraisal calibration linked to team attrition. | Python, pandas |
| [**Claims Data QA Automation**](https://github.com/mprantikk/claims-data-qa-automation) | Cleans messy EHR extracts, runs 12 declarative integrity checks, quarantines bad rows and produces an HTML failure panel. | Python, pandas |
| [**RCM Revenue Benchmarking**](https://github.com/mprantikk/rcm-revenue-benchmarking) | Scores the five core RCM KPIs (days in AR, denial rate, clean claim rate, net collection, charge lag) by payer against industry targets. | Python, MySQL |
| [**SQL Revenue Analytics**](https://github.com/mprantikk/sql-revenue-analytics) | RFM segmentation, cohort retention and CLV in SQL, with a PL/pgSQL data-quality suite. | PostgreSQL |

**Dashboards, products and research**

| Project | What it is | Built with |
|---|---|---|
| [**FMCG Sales & Distribution (Power BI)**](https://github.com/mprantikk/fmcg-sales-powerbi) | Star-schema sales model (3 facts, 6 dimensions) with 30+ DAX measures for targets, strike rate, drop size and numeric distribution, plus sales-app data-quality rules. | Power BI, DAX, Python |
| [**Growth Ops Dashboard**](https://github.com/mprantikk/growth-ops-dashboard) ([live](https://mprantikk.github.io/growth-ops-dashboard/)) | ARR, net revenue retention, churn, time to launch and cohort retention for a B2B healthtech platform. | Python, Chart.js |
| [**Perfexio**](https://github.com/mprantikk/perfexio-saas) ([live demo](https://staging-perfexio-demo.web.app/)) | Multi-tenant platform for OKR goals, manager reviews, culture scoring, and leadership dashboards. One weighted score per person: goals 50%, manager review 40%, culture 10%. | JavaScript, Firebase, Chart.js |
| [**AI Insight Quality Evaluation**](https://github.com/mprantikk/ai-insight-quality-evaluation) | My framework for judging AI-generated insights, plus a Python implementation: FDR-controlled validity, novelty scoring and panel reliability (ICC). | Python, research |

## Research

**[Beyond the Dashboard: A Conceptual Framework for Evaluating Insight Quality in AI-Augmented Business Intelligence Systems](https://mprantikk.github.io/resume/paper.html)**

BI tools now write their own insights, but few teams have a standard for checking them. The Insight Quality Evaluation (IQE) Framework scores an insight on four things:

- **Statistical validity:** the pattern is real, not noise or overfitting
- **Contextual relevance:** it bears on a decision someone is actually making
- **Novelty:** it adds something the organization does not already know
- **Actionability:** it points to a clear, feasible action

It is a conceptual paper. Empirical testing is listed as future work.

## Career

| Period | Role | Company | Field |
|---|---|---|---|
| Jan 2025 to now | Lead, Data Ops | Commure | Healthcare technology, RCM |
| Jul 2024 to Jan 2025 | Senior Data Analyst | Porter | Logistics |
| Feb 2022 to Jul 2024 | Automation & Analytics Expert | ShopUp | E-commerce and fintech |
| Dec 2020 to Jan 2022 | Business Intelligence Executive | Grameen Danone Foods | FMCG |
| Dec 2019 to Dec 2020 | Business Development Specialist | Mind Mapper Bangladesh | Training and marketing |

Recognition: Star Achiever Award (ShopUp, Q1 and Q2 2023) and Commando Award (Grameen Danone Foods, 2021).

## Say hello

<p align="center">
  <img src="assets/footer.svg" alt="Let's turn data into growth. Open to remote roles." width="100%">
</p>

<p align="center">
  <a href="mailto:mprantikk@gmail.com">mprantikk@gmail.com</a> · <a href="https://mprantikk.github.io/">mprantikk.github.io</a> · <a href="https://www.linkedin.com/in/mprantikk">LinkedIn</a>
</p>
