# Ayush Kumar

Backend-leaning full-stack. Bengaluru, India · B.Tech CSE, 2027.

[Portfolio](https://ayush-kumar-navy.vercel.app/) · [LinkedIn](https://linkedin.com/in/ayushh-o1) · [Email](mailto:ayushh.pvt10@gmail.com) · [LeetCode](https://leetcode.com/u/tZbaWZwiWk/)

Most of what I build ends up being server-side: multi-tenant isolation, job queues that survive a restart, WebSocket state that has to stay correct while several people are looking at it. I tend to spend about as long on the part that proves something works as on the thing itself.

## Now

Wrapping up **[Velora](https://github.com/Ayush-o1/velora)** — a session-booking marketplace on Django and Next.js, built around one hard requirement: a one-seat session must never be double-booked, and that has to be demonstrable rather than asserted.

Before that, **Argus**, which is the largest thing I've built and the one I'd most want to be asked about.

## Selected work

### [Argus](https://github.com/Ayush-o1/Argus) — graph investigation platform on synthetic data

A world of 70 cities across 50 countries, procedurally generated down to the transactions — roughly 20K nodes and 90K relationships, none of it real. Neo4j with the GDS plugin runs PageRank, Louvain communities and cycle detection; scikit-learn does transaction anomaly detection; FastAPI serves it and a Next.js frontend draws it as a Cytoscape graph and a deck.gl map.

The part worth looking at is the honesty layer. Argus scores its own detectors against ground truth the model never reads and publishes the precision and recall it gets, and a test fails the build if any UI surface reads the generator's answer key.

`Python` · `FastAPI` · `Neo4j + GDS` · `PostgreSQL` · `Next.js` · `TypeScript` — ~74k lines, 55 test files, CI, 12 docs

The [hosted instance](https://argus-rosy-one.vercel.app) is the landing page only — the graph backend runs locally.

### [Project 042-X](https://github.com/Ayush-o1/Project-042-X) — codebase intelligence

Give it a public GitHub URL and it clones the repo, parses every file to an AST with SWC, builds the dependency graph and reads the full git history. Tarjan's SCC finds the circular dependencies; Dagre layout is pushed into a Web Worker so a few thousand nodes don't freeze the tab.

`TypeScript` · `React` · `Node.js` · `Express` · `SWC` — 152 tests across 20 files

**[Try it](https://project-042-x.vercel.app/)** — the backend sleeps on free hosting, so the first analysis takes a moment.

### [StarGate](https://github.com/Ayush-o1/StarGate) — workflow orchestration

Wire HTTP calls and conditionals into a DAG on a canvas and hit run. Kahn's algorithm produces the execution order and catches cycles on the way; a standalone BullMQ worker runs the jobs with exponential backoff, and a second queue handles cron triggers.

Every outbound call passes a DNS-pinned SSRF guard that re-resolves and re-checks the IP on each redirect — blocking private ranges and `169.254.169.254` without also blocking Cloudflare, which it did at first.

`TypeScript` · `Node.js` · `PostgreSQL` · `Prisma` · `Redis` · `BullMQ` · `React Flow` · `Docker` · `Turborepo`

### [BlackWater](https://github.com/Ayush-o1/BlackWater) — multi-tenant incident management

Incidents move through a four-state lifecycle and a public status page reflects it live. Six Socket.IO event types drive targeted React Query invalidation rather than polling, and the JWT issued at login is reused for the socket handshake instead of inventing a second auth path.

Tenant isolation is enforced in the query layer, and a cross-org request returns 404 rather than 403 — a 403 would confirm the resource exists.

`TypeScript` · `Express` · `PostgreSQL` · `Prisma` · `Socket.IO` · `React` — CI runs the suite against a real Postgres service

<details>
<summary>Other things I've built</summary>

<br>

**[ContextForge](https://github.com/Ayush-o1/contextforge)** — an OpenAI-compatible proxy you point your app at instead of the provider. Semantic caching over FAISS and Redis, rule-based routing between model tiers, context compression on long conversations, and telemetry for what it saved you. FastAPI, forwarding through LiteLLM. Built with three others at the RIFT hackathon, where it placed runner-up; I was on architecture.

**[Velora](https://github.com/Ayush-o1/velora)** — session marketplace on Django 5 and Next.js 16, four containers behind a single Nginx port. GitHub OAuth in, JWT out.

**[CareIQ](https://github.com/Ayush-o1/cura-readmission-prediction)** — predicts 30-day hospital readmission and explains the prediction with SHAP instead of returning a bare score. XGBoost over a star-schema warehouse, Airflow-orchestrated ETL.

**[Sentinel](https://github.com/Ayush-o1/sentinel)** — spam classification for email and SMS with confidence scores, served behind a web UI. Python, scikit-learn, FastAPI.

</details>

## Proving it works

Three habits that don't show up in a language chart:

- **Velora** ships a `prove_concurrency` management command whose only job is to fire N concurrent bookings at a one-seat session, on real threads with real database connections, and report what happened. `select_for_update` inside a transaction is the answer; the command is the receipt. [`DECISIONS.md`](https://github.com/Ayush-o1/velora/blob/main/DECISIONS.md) records the two approaches I rejected and why.

- **StarGate** treats its SSRF guard as something to verify rather than assume. `ssrf.verify.ts` sits next to the guard and walks a table of cases — loopback, every private range, the cloud metadata endpoint — asserting each verdict. The Cloudflare case is in there because the guard got it wrong once.

- **Argus** publishes what it cannot detect. Two of its planted storylines leave no signal an honest detector could reach, so their recall is 0 — printed with the reason beside it, rather than dropped from the average to make the rest of the numbers look better.

## What I reach for

**Server** — Node/Express and FastAPI, mostly TypeScript and Python. Postgres by default, Prisma when it's Node. Redis and BullMQ for anything that shouldn't happen inside a request. Neo4j on Argus, because the questions there were genuinely graph questions.

**Client** — React with TanStack Query and Tailwind; Next.js on the newer work. Enough to build the front end my backend needs, and I enjoy it more than I expected to.

**Around it** — Docker Compose for local infra, GitHub Actions, pytest and Vitest, Turborepo where the monorepo earned it.

**Also** — C++ for data structures and algorithms, around 250 problems in. Django on Velora, which was my first time with it.

## Reaching me

Seventh semester now, graduating 2027, and looking for software engineering roles — backend or full-stack. Email is the fastest way to get me.

[Portfolio](https://ayush-kumar-navy.vercel.app/) · [LinkedIn](https://linkedin.com/in/ayushh-o1) · [ayushh.pvt10@gmail.com](mailto:ayushh.pvt10@gmail.com)
