# Ayush Kumar

Backend engineer. AI infrastructure builder. CS student graduating 2027.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ayushh-o1)&nbsp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ayushh.pvt10@gmail.com)&nbsp;
![](https://img.shields.io/badge/Bengaluru%2C%20India-333?style=flat-square)&nbsp;
![](https://img.shields.io/badge/Open%20to%20Internships-22c55e?style=flat-square)

---

I build backend systems and LLM infrastructure tools. Not toy projects — systems I'd stake my reputation on in a technical interview.

My engineering philosophy is simple: **correctness over cleverness, observability over opacity, boring technology when it works, new technology when it's clearly better**. I write software the way I'd want to inherit it — clean contracts, explicit behavior, no magic in the critical path.

I'm interested in the hard parts: multi-provider LLM routing, semantic caching, distributed consensus, fault-tolerant replication, and the infrastructure that makes AI systems reliable at scale.

Currently studying Kubernetes internals and Raft consensus. Building request tracing and streaming into ContextForge. Looking for internship roles where I can do real work alongside engineers who take the craft seriously.

---

## Work

### AI Infrastructure

**[ContextForge](https://github.com/Ayush-o1/contextforge)** — OpenAI-compatible LLM proxy gateway

The problem: every application needs to talk to an LLM, but direct API calls are expensive, fragile, and tied to a single provider. ContextForge sits in the middle. It provides semantic caching to eliminate redundant API calls, multi-provider routing with configurable fallback and retry logic, and context compression that reduces token overhead before requests reach the model. Deployed on Railway with a GitHub Actions CI/CD pipeline. Designed as a production drop-in, not an academic exercise.

*FastAPI · Redis · Docker · Railway · GitHub Actions*

---

**[AutoPrompt](https://github.com/Ayush-o1/autoprompt)** — Prompt optimization and evaluation engine

Prompt engineering is usually an undisciplined art. AutoPrompt treats it as a software engineering problem: versioned, testable, reproducible. YAML-driven template system with automated scoring pipelines. The eval suite runs on every commit via GitHub Actions. Integrates Gemini API. The goal is prompt changes you can review, test, and roll back.

*FastAPI · Docker · GitHub Actions · Gemini API*

---

### Backend Platforms

**[FreightFlow](https://github.com/Ayush-o1/FreightFlow)** — Role-based logistics backend

A backend platform that demonstrates real production architecture, not just CRUD endpoints. JWT authentication with structured middleware. RBAC enforced across three actor types: shipper, driver, admin. Clean route/controller/model separation. Every permission boundary is explicit and tested. Built to the standard I'd want to review in a real codebase.

*Node.js · Express · MongoDB · JWT*

---

**[Onboarder](https://github.com/Ayush-o1/Onboarder)** — Developer environment automation

Paste a GitHub URL. Get a working Docker environment. Eliminates the "clone and configure for two hours" experience for new contributors joining MERN stack projects. One command. Zero manual steps.

*Node.js · React · Docker*

---

## Stack

**Primary:** Python · JavaScript · C++

**Backend:** FastAPI · Node.js · Express

**Data:** PostgreSQL · MongoDB · Redis

**Infrastructure:** Docker · GitHub Actions · Linux · Git

**Learning:** Kubernetes · Raft consensus · Fault-tolerant replication · Cloud-native patterns

---

## Currently

Extending ContextForge with per-request cost tracking, streaming response support, and a distributed tracing layer. Studying the Kubernetes control plane and distributed consensus algorithms. Reading *Designing Data-Intensive Applications*.

---

## Contact

I respond quickly. If something here is interesting, reach out.

- **LinkedIn:** [linkedin.com/in/ayushh-o1](https://linkedin.com/in/ayushh-o1)
- **Email:** [ayushh.pvt10@gmail.com](mailto:ayushh.pvt10@gmail.com)
- **GitHub:** [github.com/Ayush-o1](https://github.com/Ayush-o1)

*Available for backend, AI/ML infrastructure, and platform engineering internships. Bengaluru-based, open to remote.*
