<a href="https://ayush-kumar-navy.vercel.app/"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/masthead-dark.svg"><img src="assets/masthead-light.svg" alt="Ayush Kumar, backend software engineer, Bengaluru" width="560"></picture></a>

Mostly backend: APIs, job queues and data models. I build the frontend too when a project needs one.

I spend about as long convincing myself something works as I do building it. Every project below ships with a written list of what it can't do.

Final-year B.Tech in Computer Science at Jain (Deemed-to-be University), graduating June 2027. Looking for SDE and software engineer roles: [ayushh.pvt10@gmail.com](mailto:ayushh.pvt10@gmail.com)

## Selected work

### [Argus](https://github.com/Ayush-o1/Argus)

A graph investigation platform over a synthetic world of 70 cities and 50 countries, with no real people in it. FastAPI serves graph analytics from Neo4j. PostgreSQL holds identity, provenance and a durable job queue. The largest thing I've built.

> It scores its own detectors against ground truth they cannot read, then publishes the storylines they miss.

<sub>Python, FastAPI, Neo4j, PostgreSQL, Redis, Next.js</sub>

### [BlackWater](https://github.com/Ayush-o1/BlackWater)

Multi-tenant incident management with a public status page. Each change to an incident locks the row, checks the lifecycle and writes its audit entry in one transaction.

> A cross-org request returns 404, not 403. A 403 would confirm the resource exists.

<sub>Node.js, Express, PostgreSQL, Prisma, Socket.IO</sub>

### [BeetleJuice](https://github.com/Ayush-o1/BeetleJuice)

Settlement reconciliation on synthetic payment data. It compares a merchant's ledger with a processor's settlement file and gives every record exactly one explained outcome.

> A fix needs a second person. Self-approval is refused by the API and again by a database trigger.

<sub>Node.js, Express, PostgreSQL, plain SQL</sub>

## More projects

- **[theRedArmy](https://github.com/Ayush-o1/theRedArmy)**: regression testing for LLM prompts. Workers claim jobs from PostgreSQL with `SKIP LOCKED`, and a CI gate fails the build when a prompt change breaks a case that used to pass. Team project.
- **[deadLetter](https://github.com/Ayush-o1/deadLetter)**: an action firewall for AI agents, after the CaMeL paper. Every value carries a label for where it came from, so injected text can't choose which tool runs. A research prototype.
- **[Europa](https://github.com/Ayush-o1/Europa)**: links successive satellite close-approach reports into one event and tracks how the predicted miss distance moves. An analysis tool, not a collision-avoidance system.

## Stack

**Most days:** JavaScript, Node.js, Express, PostgreSQL, Prisma<br>
**In specific projects:** Python and FastAPI, Neo4j, Redis, Socket.IO<br>
**Testing and delivery:** Vitest, Supertest, Playwright, pytest, Docker, GitHub Actions<br>
**Interfaces:** HTML, CSS and JavaScript, no framework<br>
**Still learning:** React and TypeScript, which Argus's frontend is written in

C++ is what I use for data structures and algorithms on [LeetCode](https://leetcode.com/u/tZbaWZwiWk/).

## Contact

Email is the fastest way to reach me: [ayushh.pvt10@gmail.com](mailto:ayushh.pvt10@gmail.com)

[Portfolio](https://ayush-kumar-navy.vercel.app/), [LinkedIn](https://linkedin.com/in/ayushh-o1)

<sub>Away from code: video editing, space, and more history and geopolitics than is probably useful. Films too. I'll sit through a bad one just to see how it ends.</sub>
