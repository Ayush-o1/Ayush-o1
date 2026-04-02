# Ayush Kumar

**Backend Engineer** · B.Tech CSE, 6th Semester · Bangalore

I build backend infrastructure and developer tools. Currently shipping [ContextForge](https://github.com/Ayush-o1/contextforge) — an OpenAI-compatible LLM proxy with semantic caching, model routing, and context compression.

**Open to Summer / Fall 2026 internships** — backend, platform engineering, infra, developer tooling.

[![Resume](https://img.shields.io/badge/Resume-4285F4?style=flat-square&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1kxhlvHqskwSOJeUYulpRN-Qe_HNPuN1w/view?usp=drive_link)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayushh-o1/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ayushh.pvt10@gmail.com)

---

## ContextForge

**OpenAI-compatible LLM gateway that reduces API costs by up to 60% — zero code changes.**

Point your existing app at `localhost:8000` instead of `api.openai.com`. Same SDK, same API, same code. The proxy handles optimization transparently:

```
Client → ContextForge Proxy
           ├─ Context Compression    (summarize long conversations → fewer tokens)
           ├─ Semantic Cache         (FAISS + Redis, ≥92% cosine similarity → <30ms hit)
           ├─ Smart Router           (simple queries → gpt-3.5 | complex → gpt-4o)
           ├─ Telemetry              (SQLite, per-request structured logging)
           └─ Upstream API response
```

Ships with a real-time analytics dashboard. Fully containerized.

`Python` · `FastAPI` · `Redis` · `FAISS` · `Docker` · `SQLite`

→ [**github.com/Ayush-o1/contextforge**](https://github.com/Ayush-o1/contextforge)

---

## Selected Work

**[AtomicTrade](https://github.com/Ayush-o1/AtomicTrade)** — Lock-free order book matching engine in C++20. Built for low-latency trade matching, validated against real NASDAQ ITCH 5.0 data.

**[GridPulse](https://github.com/Ayush-o1/GridPulse)** — Real-time streaming + OLAP warehouse for power-grid meter data. Live anomaly detection and historical analytics.

**[Onboarder](https://github.com/Ayush-o1/Onboarder)** — Paste a GitHub URL → get a running Docker dev environment in minutes. Eliminates onboarding friction.

---

## Tech

**Primary:** Python · FastAPI · PostgreSQL · Redis · Docker · Linux
**Also worked with:** Node.js · Express · MongoDB · Nginx · C++ · Git
