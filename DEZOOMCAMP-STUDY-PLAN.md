# Data Engineering Zoomcamp — Study Plan & Progress Tracker

DataTalks.Club Data Engineering Zoomcamp. Free, 9 weeks, build an end-to-end pipeline from scratch.

- Repo: https://github.com/DataTalksClub/data-engineering-zoomcamp
- Video playlist: https://www.youtube.com/playlist?list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb
- Homework / deadlines platform: https://courses.datatalks.club/
- Slack: https://datatalks.club/slack.html → `#course-data-engineering`
- Telegram announcements: https://t.me/dezoomcamp
- FAQ: https://datatalks.club/faq/data-engineering-zoomcamp.html

_Plan created 2026-06-18. Next live cohort starts January 2027. This plan is set up for self-paced study now, switching to the live cohort for the certificate if you want one._

## Prerequisites (check before starting)

- [ ] Basic coding experience
- [ ] Familiarity with SQL
- [ ] Python (helpful, not required) — recommended to be comfortable before Module 3
- [ ] Command line basics
- [ ] GitHub account + Git installed
- [ ] Google Cloud account (free tier) created — **set a billing budget/alert immediately**

## Live vs self-paced

| | Live cohort | Self-paced |
|-|-|-|
| Start | January 2027 | Anytime (now) |
| Homework | Graded + leaderboard | Self-checked |
| Peer review | Yes | No |
| Certificate | Yes (requires final project in a cohort) | No |
| Cost | Free | Free |

You can do the whole course now self-paced, then re-do the project in the Jan 2027 cohort if you want the certificate.

## The stack you'll learn

Docker · Terraform · GCP · PostgreSQL · Kestra · dlt · BigQuery · dbt · Bruin · Apache Spark · Kafka

## Syllabus & progress

Suggested pace: ~1 module per week (some take 2). The full course is ~9 weeks live.

### Module 1 — Containerization & Infrastructure as Code  → `01-docker-terraform/`
Docker & Docker Compose, Postgres in Docker, GCP intro, Terraform.
- [ ] Watch lectures
- [ ] Follow along / build locally
- [ ] Homework submitted

### Module 2 — Workflow Orchestration  → `02-workflow-orchestration/`
Data lakes, orchestration with Kestra.
- [ ] Watch lectures
- [ ] Follow along
- [ ] Homework submitted

### Workshop 1 — Data Ingestion (dlt)  → `workshop1-data-ingestion-dlt/`
Reading APIs, pipeline scalability, normalization, incremental loading.
- [ ] Watch / complete workshop
- [ ] Homework submitted

### Module 3 — Data Warehousing (BigQuery)  → `03-data-warehouse-bigquery/`
BigQuery, partitioning, clustering, best practices, ML in BigQuery.
- [ ] Watch lectures
- [ ] Follow along
- [ ] Homework submitted

### Module 4 — Analytics Engineering (dbt)  → `04-analytics-engineering-dbt/`
Data modeling, dbt with DuckDB & BigQuery, testing, docs, deployment.
- [ ] Watch lectures
- [ ] Follow along
- [ ] Homework submitted

### Module 5 — Data Platforms (Bruin)  → `05-data-platforms-bruin/`
End-to-end pipelines with Bruin: ingestion, transformation, quality, deploy to BigQuery.
- [ ] Watch lectures
- [ ] Follow along
- [ ] Homework submitted

### Module 6 — Batch Processing (Spark)  → `06-batch-processing-spark/`
Apache Spark, DataFrames & SQL, internals of GroupBy and Joins.
- [ ] Watch lectures
- [ ] Follow along
- [ ] Homework submitted

### Module 7 — Streaming (Kafka)  → `07-streaming-kafka/`
Kafka, Kafka Streams & KSQL, schema management with Avro.
- [ ] Watch lectures
- [ ] Follow along
- [ ] Homework submitted

### Final Project  → `final-project/`
End-to-end pipeline applying everything. Peer-reviewed (required for certificate).
- [ ] Pick dataset
- [ ] Build pipeline (ingestion → warehouse → transform → dashboard)
- [ ] Write README
- [ ] Submit + complete peer reviews

## Tips to actually finish (most people don't)

- Do the homework, don't just watch. The hands-on work is where it sticks.
- Push everything to GitHub from day one — the final project doubles as a portfolio piece.
- Set a GCP billing alert early; accidental charges are the #1 complaint.
- Get unstuck in Slack `#course-data-engineering` fast instead of grinding alone.
- "Learn in public" — post progress on LinkedIn/Twitter; it builds accountability and network.

## Folder layout

Each module folder has `notes/`, `homework/`, and `code/`. Keep your written notes in `notes/`, your homework answers/submissions in `homework/`, and any follow-along or experiment code in `code/`.
