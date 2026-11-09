# Ayush Kumar

**Mostly backend — APIs, queues, and data models — and the frontend when a project needs one.**

B.Tech CSE '27 · Bengaluru, India  
Looking for software development / software engineer roles.

I spend about as long convincing myself something works as I do building it. Most of my projects ship with a script whose only job is to try to break them, and that's usually the part I enjoy most.

Right now I'm building [Argus](https://github.com/Ayush-o1/Argus) — the biggest thing I've taken on so far, and nowhere near done.

Outside code I love editing video, follow space, and read more history and geopolitics than is probably useful. Films too, though I'll sit through a bad one just to see how it ends.

## Selected work

**[Argus](https://github.com/Ayush-o1/Argus)** — A graph investigation platform built entirely on generated data: 70 cities, 50 countries, no real people anywhere in it. Neo4j runs the graph analytics and scikit-learn finds the anomalies. It grades its own detectors against ground truth and publishes the cases it gets wrong.  
*Python, FastAPI, Neo4j, Next.js*

**[BlackWater](https://github.com/Ayush-o1/BlackWater)** — Multi-tenant incident management with a live status page. A cross-org request returns 404 rather than 403, because a 403 would confirm the resource exists. Every incident change and its audit entry are written in the same transaction.  
*Node.js, Express, PostgreSQL, Prisma, Socket.IO*

**[theRedArmy](https://github.com/Ayush-o1/theRedArmy)** — Self-hosted regression testing for LLM prompts, built as a team project. A run becomes one job per test case; workers claim them from PostgreSQL with `SKIP LOCKED` and share a Redis rate limit, and a CI endpoint fails the build when a prompt change breaks a case that used to pass.  
*Node.js, Express, PostgreSQL, Redis*

**[BeetleJuice](https://github.com/Ayush-o1/BeetleJuice)** — Settlement reconciliation on synthetic payment data: it compares a merchant's ledger with a processor's settlement file and explains every difference. Fixing a break needs a second person to approve it, and self-approval is refused in the database as well as the API.  
*Node.js, Express, PostgreSQL*

**[deadLetter](https://github.com/Ayush-o1/deadLetter)** — An action firewall for AI agents, based on the CaMeL design. The planner never sees the emails or pages the agent reads, and every value is labelled with where it came from, so injected text can't choose which tool runs or where private data goes. It's a research prototype on fake tools, and its evaluation lists the attacks that still get through.  
*Node.js, Express, PostgreSQL*

**[Europa](https://github.com/Ayush-o1/Europa)** — A workbench for public satellite close-approach reports. Each report is a snapshot, so Europa links successive predictions for the same pair into one event, tracks how the miss distance moves, and ranks events for review on a hash-chained audit log. An analysis tool, not a collision-avoidance system.  
*Node.js, Express, PostgreSQL, satellite.js*

## Elsewhere

Email is the fastest way to reach me — [ayushh.pvt10@gmail.com](mailto:ayushh.pvt10@gmail.com)

[Portfolio](https://ayush-kumar-navy.vercel.app/) · [LinkedIn](https://linkedin.com/in/ayushh-o1) · [LeetCode](https://leetcode.com/u/tZbaWZwiWk/)

*Last updated: 9 November 2026*
