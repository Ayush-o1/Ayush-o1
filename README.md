<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a2744,100:0d1117&height=220&section=header&text=Ayush%20Kumar&fontSize=44&fontColor=e6edf3&fontAlignY=30&desc=Backend%20Engineer%20%C2%B7%20LLM%20Systems%20%C2%B7%20Developer%20Tooling&descSize=16&descColor=58a6ff&descAlignY=52&animation=fadeIn" />
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:ffffff,50:dbe4ff,100:f6f8fa&height=220&section=header&text=Ayush%20Kumar&fontSize=44&fontColor=1f2328&fontAlignY=30&desc=Backend%20Engineer%20%C2%B7%20LLM%20Systems%20%C2%B7%20Developer%20Tooling&descSize=16&descColor=0969da&descAlignY=52&animation=fadeIn" />
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a2744,100:0d1117&height=220&section=header&text=Ayush%20Kumar&fontSize=44&fontColor=e6edf3&fontAlignY=30&desc=Backend%20Engineer%20%C2%B7%20LLM%20Systems%20%C2%B7%20Developer%20Tooling&descSize=16&descColor=58a6ff&descAlignY=52&animation=fadeIn" width="100%" />
</picture>

<br/>

**B.Tech CSE, 6th Semester · Bangalore, India**

🎯 **Open to Summer / Fall 2026 Internships** — Backend · Platform · Infra · Developer Tooling

<br/>

[![Resume](https://img.shields.io/badge/Resume-4285F4?style=flat-square&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1kxhlvHqskwSOJeUYulpRN-Qe_HNPuN1w/view?usp=drive_link)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayushh-o1/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000?style=flat-square&logo=netlify&logoColor=white)](https://ayushh-portfolio-2026.netlify.app/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ayushh.pvt10@gmail.com)

</div>

<br/>

I build backend systems and developer infrastructure with a bias toward correctness and clean interfaces. Currently shipping **ContextForge** — an LLM proxy that makes cost optimization invisible to application code.

---

## Currently Building

<table>
<tr>
<td>

### [⚡ ContextForge](https://github.com/Ayush-o1/contextforge)

**OpenAI-compatible LLM gateway that reduces API costs by up to 60% — zero code changes.**

Swap `api.openai.com` for `localhost:8000`. Your existing SDK, API calls, and application code stay identical. The proxy intercepts and optimizes every request transparently:

```
Client → ContextForge Proxy
           ├─ Context Compression    (trim long conversations → fewer tokens)
           ├─ Semantic Cache         (FAISS + Redis, ≥92% cosine → <30ms hit)
           ├─ Smart Router           (simple → gpt-3.5 | complex → gpt-4o)
           ├─ Telemetry              (SQLite, per-request structured logging)
           └─ OpenAI-format response
```

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white" />
</p>

**Why it matters:** Most LLM wrappers require SDK changes or vendor lock-in. ContextForge is fully transparent — applications don't even know it's there. Ships with a real-time analytics dashboard and production-ready Docker Compose setup.

→ [**View Repository**](https://github.com/Ayush-o1/contextforge)

</td>
</tr>
</table>

---

## Selected Work

<table>
<tr>
<td width="30%"><strong><a href="https://github.com/Ayush-o1/AtomicTrade">AtomicTrade</a></strong></td>
<td>Lock-free order book matching engine in <code>C++20</code> — built for low-latency trade matching, validated against real NASDAQ ITCH 5.0 feed data</td>
</tr>
<tr>
<td><strong><a href="https://github.com/Ayush-o1/GridPulse">GridPulse</a></strong></td>
<td>Real-time streaming + OLAP warehouse for power-grid meter data — live anomaly detection, alerting, and historical analytics</td>
</tr>
<tr>
<td><strong><a href="https://github.com/Ayush-o1/Onboarder">Onboarder</a></strong></td>
<td>Paste a GitHub URL → get a running Docker dev environment in minutes. Automates repo cloning, dependency detection, and containerized setup</td>
</tr>
</table>

---

## Tech Stack

<table>
<tr>
<td><strong>Languages</strong></td>
<td>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/SQL-003B57?style=flat-square&logoColor=white" />
</td>
</tr>
<tr>
<td><strong>Backend</strong></td>
<td>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Express-000?style=flat-square&logo=express&logoColor=white" />
</td>
</tr>
<tr>
<td><strong>Data</strong></td>
<td>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
</td>
</tr>
<tr>
<td><strong>Infra</strong></td>
<td>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</td>
</tr>
</table>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Ayush-o1&layout=compact&hide=html,css&exclude_repo=truck,arrow&hide_border=true&bg_color=00000000&text_color=c9d1d9&title_color=58a6ff&langs_count=6" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Ayush-o1&layout=compact&hide=html,css&exclude_repo=truck,arrow&hide_border=true&bg_color=00000000&text_color=1f2328&title_color=0969da&langs_count=6" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ayush-o1&layout=compact&hide=html,css&exclude_repo=truck,arrow&hide_border=true&langs_count=6" width="350" />
</picture>

</div>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a2744,100:0d1117&height=120&section=footer" />
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:ffffff,50:dbe4ff,100:f6f8fa&height=120&section=footer" />
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a2744,100:0d1117&height=120&section=footer" width="100%" />
</picture>
