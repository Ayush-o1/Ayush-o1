# Ayush Kumar

**Mostly backend — APIs, queues, and data models — and the frontend when a project needs one.**

B.Tech CSE '27 · Bengaluru, India · Open to SDE / Software Engineer roles

I spend about as long convincing myself something works as I do building it. Most of my projects ship with a script whose only job is to break them, and that's usually the part I enjoy most.

---

## Selected work

### 01 · [Argus](https://github.com/Ayush-o1/Argus)

*In progress. The biggest thing I've taken on so far.*

A graph investigation platform built on generated data: 70 cities, 50 countries, no real people anywhere in it. Neo4j runs the graph analytics and scikit-learn finds the anomalies.

> It grades its own detectors against known ground truth and publishes the cases they get wrong.

`Python` `FastAPI` `Neo4j` `scikit-learn` `Next.js`

### 02 · [BlackWater](https://github.com/Ayush-o1/BlackWater)

Multi-tenant incident management with a live public status page. Every incident change and its audit entry are written in the same transaction.

> A cross-org request returns 404, not 403, because a 403 would confirm the resource exists.

`Node.js` `Express` `PostgreSQL` `Prisma` `Socket.IO`

### 03 · [BeetleJuice](https://github.com/Ayush-o1/BeetleJuice)

Settlement reconciliation on synthetic payment data. It compares a merchant's ledger with a processor's settlement file and explains every difference.

> A fix needs a second person to approve it. Self-approval is refused by the API and again by the database.

`Node.js` `Express` `PostgreSQL`

---

## More projects

- **[theRedArmy](https://github.com/Ayush-o1/theRedArmy)** — Regression testing for LLM prompts. Workers claim jobs from PostgreSQL with `SKIP LOCKED`, and CI fails the build when a prompt change breaks a case that used to pass. *Team project.*
- **[deadLetter](https://github.com/Ayush-o1/deadLetter)** — An action firewall for AI agents, based on CaMeL. Every value carries its origin, so injected text can't choose which tool runs. A research prototype, and its evaluation lists the attacks that still get through.
- **[Europa](https://github.com/Ayush-o1/Europa)** — Links successive satellite close-approach reports into one event and tracks how the miss distance moves. An analysis tool, not a collision-avoidance system.

---

## Stack

**Backend** · Node.js, Express, Python, FastAPI, Socket.IO<br>
**Data** · PostgreSQL, Prisma, Redis, Neo4j, scikit-learn<br>
**Frontend** · Next.js

---

## Elsewhere

Email is the fastest way to reach me: [ayushh.pvt10@gmail.com](mailto:ayushh.pvt10@gmail.com)

[Portfolio](https://ayush-kumar-navy.vercel.app/) · [LinkedIn](https://linkedin.com/in/ayushh-o1) · [LeetCode](https://leetcode.com/u/tZbaWZwiWk/)

<sub>Away from code: video editing, space, and more history and geopolitics than is probably useful. Films too. I'll sit through a bad one just to see how it ends.</sub>
