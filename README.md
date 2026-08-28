# Ayush Kumar

**Backend systems, and the proof they hold up.**

Bengaluru · B.Tech CSE 2027 · open to software engineering roles

[Portfolio](https://ayush-kumar-navy.vercel.app/) · [LinkedIn](https://linkedin.com/in/ayushh-o1) · [Email](mailto:ayushh.pvt10@gmail.com) · [LeetCode](https://leetcode.com/u/tZbaWZwiWk/)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img src="assets/hero-light.svg" width="100%" alt="Fifteen concurrent booking requests race for a single seat. A SELECT FOR UPDATE row lock admits exactly one, which returns 201 Created; the other fourteen return 409 Conflict.">
</picture>

<sub>Velora ships this as a runnable command — <code>prove_concurrency</code> — not just a claim in a README.</sub>

## Selected work

### [Argus](https://github.com/Ayush-o1/Argus) — graph investigation on synthetic data

[![Argus](assets/argus.jpg)](https://github.com/Ayush-o1/Argus)

A graph investigation platform over a world that doesn't exist — 70 cities, 50 countries, every entity procedurally generated. Neo4j and GDS run the analytics; scikit-learn finds the anomalies. It grades its own detectors against ground truth the model never sees, and publishes the score including the cases it fails.

`Python` `FastAPI` `Neo4j` `PostgreSQL` `Next.js` — 74k lines · 55 test files · CI

### [Project 042-X](https://project-042-x.vercel.app/) — codebase intelligence

[![Project 042-X](assets/x042.jpg)](https://project-042-x.vercel.app/)

Give it a public GitHub URL. It parses every file to an AST, builds the dependency graph, and reads the git history. Tarjan's SCC finds the circular imports; layout runs in a Web Worker so the graph doesn't freeze the tab.

`TypeScript` `React` `SWC` — 152 tests

### [StarGate](https://github.com/Ayush-o1/StarGate) — workflow orchestration

[![StarGate](assets/stargate.jpg)](https://github.com/Ayush-o1/StarGate)

Wire HTTP calls and conditionals into a DAG, hit run. Kahn's algorithm orders execution and catches cycles. Outbound calls pass a DNS-pinned SSRF guard that re-checks the resolved IP on every redirect.

`TypeScript` `Redis` `BullMQ` `Docker`

### [BlackWater](https://github.com/Ayush-o1/BlackWater) — multi-tenant incident management

[![BlackWater](assets/blackwater.jpg)](https://github.com/Ayush-o1/BlackWater)

Live public status page. Socket.IO events drive targeted cache invalidation instead of polling. A cross-org request returns 404, not 403 — a 403 would confirm the resource exists.

`TypeScript` `PostgreSQL` `Socket.IO` — CI runs against a real Postgres

<details>
<summary>Other things I've built</summary>
<br>

**[ContextForge](https://github.com/Ayush-o1/contextforge)** — OpenAI-compatible LLM proxy, semantic caching, model-tier routing. RIFT hackathon runner-up.

**[Velora](https://github.com/Ayush-o1/velora)** — session marketplace, Django 5 + Next.js 16.

**[CareIQ](https://github.com/Ayush-o1/cura-readmission-prediction)** — 30-day readmission risk, explained with SHAP.

**[Sentinel](https://github.com/Ayush-o1/sentinel)** — spam classification for email and SMS.

</details>

## Claim, then proof

- **A one-seat session can't be double-booked, even under real concurrency.** [Velora](https://github.com/Ayush-o1/velora)'s `prove_concurrency` fires 15 real threads at a live session — 1 commits, 14 get 409, reproducibly.
- **The SSRF guard blocks private ranges without also blocking legitimate hosts.** [StarGate](https://github.com/Ayush-o1/StarGate)'s `ssrf.verify.ts` asserts every address class, including the Cloudflare case it got wrong once.
- **Argus's own detectors are graded honestly, not cherry-picked.** Two planted storylines score recall 0 — printed with the reason, not dropped from the average.

## The shape of most of it

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/flow-dark.svg">
  <img src="assets/flow-light.svg" width="100%" alt="Client built with React, Next.js and TanStack Query; API in Express, FastAPI or Django; async work on BullMQ, Redis and Socket.IO; data in PostgreSQL via Prisma, or Neo4j. Docker, GitHub Actions, pytest, Vitest, Turborepo and C++ for DSA around all of it.">
</picture>

## Reaching me

Email is fastest — [ayushh.pvt10@gmail.com](mailto:ayushh.pvt10@gmail.com) — or [LinkedIn](https://linkedin.com/in/ayushh-o1) and [my portfolio](https://ayush-kumar-navy.vercel.app/).

<sub>Last updated: 28 August 2026</sub>
