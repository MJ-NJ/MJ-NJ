<div align="center">

<img src="./assets/header.svg" alt="Mrituanjay Nath Jha — terminal intro" width="100%" />

[![Portfolio](https://img.shields.io/badge/Portfolio-mrituanjay.tech-58a6ff?style=for-the-badge&logo=googlechrome&logoColor=white)](https://mrituanjay.tech/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mrituanjayjha-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mrituanjayjha/)
[![X](https://img.shields.io/badge/X-@Mrituanjay7-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Mrituanjay7)
[![Email](https://img.shields.io/badge/Email-mrituanjay2003@gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mrituanjay2003@gmail.com)

</div>

Backend engineer building distributed systems, multi-tenant databases, and backends that stay up when infrastructure doesn't. Currently a **Software Research & Development Engineer at THB**, working on core infrastructure for a multi-tenant healthcare platform, directly with the CTO on architecture.

> 🌐 **More of my work lives at [mrituanjay.tech](https://mrituanjay.tech/)**

---

## ⚡ Impact at THB

<img src="./assets/impact.svg" alt="Impact: 97% faster crash recovery, 85% lower MTTR, under 1 minute storage migration, zero data loss" width="100%" />

<br/>

<img src="./assets/pipeline.svg" alt="Outbox to CDC to broker to idempotent consumers" width="100%" />

<details>
<summary><b>The full list</b></summary>

- **Crash recovery −97%:** outbox pattern with transaction replay. 30 min of manual SQL audits became 90 s.
- **Migrations in under a minute:** per-tenant filesystem config turned a 4-hour deploy cycle into a config change.
- **MTTR −85%:** distributed tracing across services collapsed a 5-step investigation into one API call.
- **Zero data loss** through Postgres/Redis outages: at-least-once delivery and idempotent semantics.
- **No-code tenant workflows:** a DSL-based engine with ABAC/RBAC policy evaluation, so business teams configure workflows without a release.
- **CDC over polling:** change-data-capture pipelines for transactional consistency across service boundaries.
- **Grew the team:** onboarded 5 senior engineers (3 frontend, 2 backend) onto the system.

</details>

---

## 🌟 Featured Project

### 🥗 [Iksha](https://nutrition.myiksha.com) · *Aug '26 – present* · [**Try the live demo →**](https://nutrition.myiksha.com)
`Go` `Echo` `Gemini` `NVIDIA NIM` `PWA` `SQLite` `S3`

A production vision-AI service: photograph a nutrition label, get a plain-language verdict in multiple languages. Built end to end, from architecture to deployment.
- **Two-stage pipeline:** an OCR pre-check rejects non-label images before the expensive model call, then a vision-LLM call is constrained to a JSON schema with validation and fallback.
- **Dual-provider fallback:** Gemini primary, NVIDIA NIM backup, with rate limiting and concurrency tuned per provider.
- **Async persistence:** SQLite + S3 behind a bounded worker pool, so writes never block responses.

## 🧰 Also Built

### 📦 Tally Ops Automation · *Mar '26 – present*
`Python` `pandas` `Tally ODBC` `Telegram Bot API` `Gmail API`

Automation server for a hospital-supplies distributor, in daily production use. It syncs with Tally ERP and pushes low-stock alerts and daily inventory to staff phones, saving ~2 hrs/day.
- **3-tier challan status system** replaced manual Tally lookups that had caused expired, wasted stock.
- **Weekly per-company sales reports**, automated, freeing up a full workday each week.

---

## 🛠️ Stack

<img src="./assets/stack.svg" alt="Toolbox: Go, C/C++, Python, SQL, Echo, Fiber, NATS, PostgreSQL, Redis, MongoDB, Grafana, Prometheus, Docker, Linux" width="100%" />

---

<img src="./assets/now.svg" alt="Status: building Iksha, shipping at THB, exploring low-latency systems" width="100%" />

<p align="center">
  <img src="https://raw.githubusercontent.com/MJ-NJ/MJ-NJ/output/snake.svg" alt="Snake animation" width="60%" />
</p>
