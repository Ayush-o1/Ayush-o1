<div align="center">

# Ayush Kumar

### Backend systems designed around the failure case, not the happy path.

B.Tech CSE '27 · Bengaluru, India · Open to Software Engineer (SWE) roles

[![LinkedIn](https://img.shields.io/badge/LinkedIn-e6edf3?style=flat-square&logo=linkedin&logoColor=0d1117)](https://linkedin.com/in/ayushh-o1)
[![Email](https://img.shields.io/badge/Email-e6edf3?style=flat-square&logo=gmail&logoColor=0d1117)](mailto:ayushh.pvt10@gmail.com)
[![GitHub](https://img.shields.io/badge/Ayush--o1-e6edf3?style=flat-square&logo=github&logoColor=0d1117)](https://github.com/Ayush-o1)

<br>

**3** Production Systems&nbsp;&nbsp;·&nbsp;&nbsp;**200+** DSA Problems Solved&nbsp;&nbsp;·&nbsp;&nbsp;**SIH Internal** • 3rd Place

<br>

[`BlackWater`](#blackwater) &nbsp;·&nbsp; [`StarGate`](#stargate) &nbsp;·&nbsp; [`FreightFlow`](#freightflow)

</div>

<br>

---

<br>

<div align="center">

## Featured Projects

</div>

<br>

<div align="center">

![](https://img.shields.io/badge/-STATUS_PAGE_PLATFORM-f85149?style=flat-square)

### [BlackWater](https://github.com/Ayush-o1/BlackWater)

**When something breaks, someone declares it — and the public status page updates itself. No cron job. No manual toggle.**

<img src="https://github.com/Ayush-o1/BlackWater/raw/main/screenshots/02_dashboard.png" width="100%" />

</div>

- Incident lifecycle is a strict, forward-only state machine — closed incidents are immutable at the database layer
- Service health is derived automatically from active incidents; nobody flips a status by hand
- Public API strips internal fields via DTO isolation before anything leaves the server

`TypeScript` `Node.js` `Express` `PostgreSQL` `Prisma` `Socket.IO` `React`

<br>

---

<br>

<div align="center">

![](https://img.shields.io/badge/-WORKFLOW_AUTOMATION_ENGINE-a371f7?style=flat-square)

### [StarGate](https://github.com/Ayush-o1/StarGate)

**Wire HTTP calls and conditionals into a visual graph, hit run — a worker fleet executes it in dependency order, retries included.**

<img src="https://github.com/Ayush-o1/StarGate/raw/main/docs/screenshots/workflow-canvas.png" width="100%" />

</div>

- Kahn's algorithm topologically sorts the DAG before a single node runs; cycles are rejected before enqueue
- Every outbound call passes a DNS-resolve + CIDR SSRF guard first — all RFC 1918 ranges blocked
- The API responds in milliseconds; BullMQ retries failed nodes with exponential backoff, decoupled from execution time

`TypeScript` `Node.js` `BullMQ` `Redis` `PostgreSQL` `React Flow` `Docker`

<br>

---

<br>

<div align="center">

![](https://img.shields.io/badge/-LOGISTICS_SAAS_BACKEND-3fb950?style=flat-square)

### [FreightFlow](https://github.com/Ayush-o1/FreightFlow)

**Shippers request, drivers deliver, admins watch it update live — with idempotency keys standing between a slow network and a duplicate charge.**

<img src="https://github.com/Ayush-o1/FreightFlow/raw/main/docs/screenshots/login.png" width="100%" />

</div>

- Shipment status is forward-only and enforced server-side — the client is never trusted with state transitions
- Every critical mutation requires an idempotency key; the outbox pattern durably logs state before async work runs
- Full cloud-native footprint — Kubernetes, Terraform, Prometheus + Grafana, with documented disaster-recovery runbooks

`Node.js` `Express` `MongoDB` `Redis` `Socket.IO` `Kubernetes` `Terraform`

<br>

---

<br>

<div align="center">

## Other Projects

</div>

<br>

**[CareIQ](https://github.com/Ayush-o1/cura-readmission-prediction)** — Predicts which patients are likely to be readmitted within 30 days of discharge, and explains why with SHAP instead of a black-box score. XGBoost scoring 0.84 AUROC on a star-schema warehouse, Airflow-orchestrated ETL.
`Python` `FastAPI` `XGBoost` `Airflow` `PostgreSQL`

**[AutoPrompt](https://github.com/Ayush-o1/auto-Prompt)** — Treats prompt engineering as a versioned software artifact: YAML-driven prompts with automated scoring on every commit.

**[SwitchBoard](https://github.com/Ayush-o1/switchboard)** — Self-hosted LLM gateway that routes across OpenAI, Anthropic, Gemini, and HuggingFace with automatic failover, serving repeated prompts from a two-pass semantic cache in milliseconds at zero cost.
`Python` `FastAPI` `PostgreSQL` `pgvector` `Docker`

<br>

---

<br>

<div align="center">

## Tech Stack

<br>

**Languages**
<img src="https://skillicons.dev/icons?i=ts,js,python,cpp" />

<br><br>

**Backend & Data**
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,postgres,mongodb,redis" />

<br><br>

**Frontend**
<img src="https://skillicons.dev/icons?i=react,tailwind" />

<br><br>

**Infrastructure**
<img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,githubactions,git" />

<br><br>

**Core CS**

🧩 **Data Structures & Algorithms**&nbsp;&nbsp;·&nbsp;&nbsp;⚙️ **Operating Systems**&nbsp;&nbsp;·&nbsp;&nbsp;🗄️ **DBMS**&nbsp;&nbsp;·&nbsp;&nbsp;🌐 **Computer Networks**

🏛️ **OOP**&nbsp;&nbsp;·&nbsp;&nbsp;📐 **System Design**&nbsp;&nbsp;·&nbsp;&nbsp;🔗 **Distributed Systems**

</div>

<br>

---

<br>

<div align="center">

## GitHub Activity

<br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ayush-o1&theme=github-compact&bg_color=0d1117&color=8b949e&line=6e7681&point=e6edf3&hide_border=true&area=true" width="100%" />

</div>

<br>

---

<br>

<div align="center">

### Open to Software Engineer (SWE) roles — batch of 2027

[![LinkedIn](https://img.shields.io/badge/LinkedIn-e6edf3?style=flat-square&logo=linkedin&logoColor=0d1117)](https://linkedin.com/in/ayushh-o1)
[![Email](https://img.shields.io/badge/Email-e6edf3?style=flat-square&logo=gmail&logoColor=0d1117)](mailto:ayushh.pvt10@gmail.com)
[![GitHub](https://img.shields.io/badge/Ayush--o1-e6edf3?style=flat-square&logo=github&logoColor=0d1117)](https://github.com/Ayush-o1)

<br>

Last Edited on: 4 July 2026

</div>
