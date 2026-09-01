<h1 align="center">Naphat Pothibuathong</h1>

<p align="center">
  Computer Engineering @ <b>Kasetsart University</b> (Bangkhen), class of 2028<br>
  I build data pipelines — Python, SQL, Airflow, Docker.<br>
  <b>Looking for a Data Engineering internship in Bangkok.</b>
</p>

<p align="center">
  <a href="mailto:stampnapatt@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/stampnapat?tab=repositories"><img src="https://img.shields.io/badge/Projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="Projects"></a>
  <img src="https://img.shields.io/badge/Bangkok,%20Thailand-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Bangkok">
</p>

---

## Tech Stack

**Data Engineering**

<p>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white">
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white">
  <img src="https://img.shields.io/badge/Delta%20Lake-00ADD4?style=for-the-badge&logoColor=white">
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
</p>

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black">
</p>

**Backend / Databases**

<p>
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
</p>

**Tools**

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white">
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
</p>

---

## What I've built

### [stock-pipeline](https://github.com/stampnapat/stock-pipeline) — daily ELT pipeline

Yahoo Finance → PostgreSQL → SQL window functions (MA-7, MA-30, daily return) → Streamlit dashboard.
Scheduled with Airflow (Mon–Fri, catchup off), idempotent upserts so a re-run never duplicates a row,
whole stack comes up with one `docker compose up`.

`Python` · `PostgreSQL` · `Airflow` · `Docker` · `Streamlit`

### [CREDIT_PROJECT](https://github.com/stampnapat/CREDIT_PROJECT) — KU Credit Tracker API

Express 5 + TypeScript on a deliberate dual-database design: MySQL via Prisma where referential
integrity matters, MongoDB via Mongoose where the documents need to stay flexible.
JWT auth with role-based access, soft delete with restore, 32 Jest tests, Swagger docs.

`TypeScript` · `Express` · `Prisma` · `MySQL` · `MongoDB` · `Jest`

---

## Databricks Data Engineer program — 15 modules

Structured training I'm finishing alongside coursework, working through Databricks notebooks module by module:

- **PySpark** (modules 6–7) — DataFrame API, joins, window functions, partitioning, UDFs
- **Delta Lake** (modules 8–10) — ACID tables, constraints, Change Data Feed, time travel,
  `MERGE` strategies, **SCD Type 1 & 2**, OPTIMIZE / Z-ORDER / VACUUM
- **Medallion architecture** (modules 4, 11) — bronze → silver → gold, end-to-end framework project
- **Unity Catalog** (modules 13–14) — governance, lineage, data privacy and masking
- **SQL for data engineering** (modules 2–3) and **Python / OOP process design** (modules 4–5)

---

## Stats

<p align="center">
  <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=stampnapat&theme=tokyonight" alt="GitHub stats">
  <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=stampnapat&theme=tokyonight" alt="Most used languages">
</p>

<p align="center">
  <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=stampnapat&theme=tokyonight&utcOffset=7" alt="Productive time">
  <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=stampnapat&theme=tokyonight" alt="Repos per language">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=stampnapat&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub streak">
</p>

---

## Currently working on

Bringing what I learned in the Databricks program back into `stock-pipeline` — a proper warehouse
layer with star schema, fact/dimension tables and SCD Type 2, and rewriting the transform step in
PySpark so it holds up on datasets that outgrow a single Postgres box.

## Reach me

**stampnapatt@gmail.com** · Bangkok, Thailand
