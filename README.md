<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,12,20,24&height=160&section=header&text=Prabhav%20Bansal&fontSize=40&fontAlign=72&animation=fadeIn&fontColor=ffffff&desc=Engineer%20%C2%B7%20Founder&descAlign=72&descAlignY=75&descSize=20" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Backend+systems+%26+data+infrastructure;Founder+%40+Nayikala+%E2%80%94+AI+growth+for+Indian+SMEs;200M%2B+rows%2Fday+%C2%B7+1B%2B+people+profiles;Search+%C2%B7+RAG+%C2%B7+MCP+%C2%B7+automation;Backend-first%2C+product-capable%2C+founder-minded" alt="Typing SVG" />

</div>

---

## About

Backend-first engineer and founder. I own messy, high-scale infrastructure problems end to end — and I build products on the side.

By day: data pipelines and AI tooling at [Crustdata](https://crustdata.com). Before that: carrier systems and telecom infrastructure at [Plivo](https://plivo.com). Most of my highest-impact work lives in private repositories — this profile is intentionally outcome-led. **Scale handled, systems shipped, problems solved** are better proxies than commit volume. Private contributions are enabled.

Founding [Nayikala](https://nayikala.com) — AI growth systems for Indian SMEs. Real ops, not theatre.

Building at the intersection of **backend systems, data infrastructure, and AI-powered products**. I care about craft: from backend reliability to the way a product actually feels when someone uses it.

- 📍 Bangalore, India · Open to remote
- 🎓 IIIT Hyderabad · JEE AIR 650 — top 0.05% of 1.2M candidates · INMO 2018 (top 50 nationally)

---

## Signature Wins

- Rebuilt a core enrichment pipeline: **50M → 200M+ rows/day** (4×) — architecture, not brute-force scaling
- Automated carrier lifecycle: **1,200 → <100 support tickets/month**, $300K/yr saved — systematic automation, not monitoring
- Shipped data products at scale: **1B+ people profiles**, **60M+ companies**, **654K+ parliamentary records**
- Nayikala client deployments: **-47% first-response time**, **-52% manual reporting**, **-38% support backlog**

---

## Founding: Nayikala

**[nayikala.com](https://nayikala.com)** — AI growth systems for Indian SMEs (10–250 employees)

Indian businesses run on WhatsApp, spreadsheets, and phone calls. Nayikala audits the operational drag, then deploys AI automation systems around the way businesses *already* work — integrating WhatsApp, email, CRM, and accounting tools into unified workflows with human oversight and measurable KPIs.

Not consulting. Not POCs. Production systems that teams actually use daily.

> **Delivery model**: Diagnose → Deploy → Improve. Fixed scope, outcome-disciplined. If numbers don't move, we keep working.

**Client outcomes so far:**
- -47% first-response time (WhatsApp lead unification)
- -52% manual reporting time (automated KPI summaries)
- -38% support backlog (AI-assisted task handling)
- +34% qualified inquiry quality (website rebuild + intelligent routing)

**Flagship product**: [Rep4Real](https://rep4real.com) — demonstrates the full automation workflow: lead intake, WhatsApp integration, inquiry routing, follow-up automation. Built to be seen working, not just described.

`Astro · Next.js · React · FastAPI · PostgreSQL · WhatsApp API · Resend · Vercel`

---

## Production Systems

<details open>
<summary><strong>Crustdata (Jul 2025 – Present) · Full-Stack Engineer</strong></summary>

**MCP Server — Natural-language B2B intelligence**
Claude, Cursor, and Windsurf users query Crustdata's real-time database in plain English. 60M+ companies, 1B+ people profiles. Now a core product in Crustdata's AI stack.
`OpenAPI · MCP · Python`
→ **60M+ companies · 1B+ people profiles**

**Spark Enrichment Pipelines**
Re-architected the core data enrichment pipeline — focused on pipeline design and data flow, not brute-force infra scaling.
`Apache Spark · Python · ClickHouse`
→ **50M → 200M+ rows/day (4×)**

**Company Profiles Platform**
End-to-end: React frontend, backend APIs, Cloudflare layer, async ETL. Drove organic discovery through architecture decisions.
`React · Kubernetes · Cloudflare · ETL`
→ **15K+ visits/day · +35% indexed pages**

</details>

<details open>
<summary><strong>Plivo (Jun 2022 – Jul 2025) · Software Engineer</strong></summary>

**Carrier Integration Platform**
Owned a fragmented carrier workflow across Bandwidth, Intelliquent, and 8ms. Solved the operational mess with lifecycle automation — not monitoring.
`Go · AWS · Microservices`
→ **1,200 → <100 support tickets/month · $300K/yr saved**

**Number Return & Recycle Pipeline**
Automated pipeline reclaiming 1,000+ numbers/day, cleaned 100K+ records. Owned the full lifecycle, not just the happy path.
`Go · PostgreSQL · Elasticsearch`
→ **1,000+ numbers/day · -30% p95 latency**

</details>

---

## Side Projects & Experiments

**[Sansad QA v2](https://github.com/prabhavbansal27/sansad-qa-v2)** *(active)*

Parliamentary fact-checking: 654,539 Q&A records from Indian Parliament (1999–present). Paste a news article → decompose into atomic claims → retrieve evidence → SUPPORTED / CONTRADICTED / UNVERIFIABLE verdicts per claim. Fully local, no API keys.

What makes it interesting: the **retrieval thinking** — hybrid BM25 + vector search with Reciprocal Rank Fusion, domain-specific query expansion (parliamentary abbreviations, fiscal year normalization), and a proper eval framework (Recall@K, MRR, NDCG@K) to measure whether it actually works.

`TypeScript · SQLite FTS5 · sqlite-vec · Ollama · Reciprocal Rank Fusion · Express`
*~6,500 lines · 6.9 GB corpus · <10ms hybrid search*

---

**[Emprix](https://github.com/prabhavbansal27/emprix)** *(active)*

Full-stack collaboration and investment platform — teams, hiring, and investment workflows in one place. Built with a production-grade async stack.

`FastAPI · PostgreSQL · Redis · Celery · React 19 · TypeScript · Tailwind v4`

---

**[Island World Portfolio](https://prabhavbansal27.github.io)**

Interactive 3D island world — entirely in the browser. Scroll-driven camera, Rapier physics, toon shaders, A* pathfinding, Web Audio beat detection, day/night cycle. Built because backend engineers should be able to ship things that are technically strong *and* actually pleasant to use.

`Three.js · React Three Fiber · Rapier · GLSL · React 19`

---

**Court Piece Companion**

Full-stack implementation of Court Piece (a South Asian trick-taking card game) with a Go game engine, AI bot opponent, and React PWA frontend. The interesting part: the bot implements the full game-state machine and rule engine, not just a lookup table.
`Go · React · TypeScript · Game AI`

**Social Content Studio**

Single-brand content pipeline: brand calibration → Gemini image generation (3 variants per request, no-text/no-watermark) → caption + hashtag generation → export. Vitest suite covering unit, integration, and e2e-style flow tests.
`Next.js · TypeScript · Gemini API · Supabase · Vitest`

**Multi-Chat PDF System**

Local PDF chat for family members who are government employees — sensitive documents that can't go to the cloud. Full-stack, runs entirely offline.
`Full-Stack · NLP · React · Local LLM`

**Linux Shell**

Bash-like shell in C — piping, I/O redirection, process management, job control, command history, built-ins.
`C · Unix · Systems`

---

## Currently Building

- **Nayikala** — Scaling client delivery, deepening vertical playbooks, building toward productized SaaS
- **Sansad QA** — Public deployment: web app + browser extension for real-time parliamentary fact-checking
- **AI Agent Architectures** — MCP servers, multi-agent workflows, natural-language interfaces for data platforms

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & Data**

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**AI / Creative**

![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)

---

## Coding Activity

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-0%20secs-blue?style=flat)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue?style=flat)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-25.39%20million%20lines%20of%20code-blue?style=flat)

**🐱 My GitHub Data** 

> 📦 1.0 MB Used in GitHub's Storage 
 > 
> 🏆 153 Contributions in the Year 2026
 > 
> 🚫 Not Opted to Hire
 > 
> 📜 3 Public Repositories 
 > 
> 🔑 18 Private Repositories 
 > 
**I'm a Night 🦉** 

```text
🌞 Morning                44 commits          █░░░░░░░░░░░░░░░░░░░░░░░░   04.10 % 
🌆 Daytime                101 commits         ██░░░░░░░░░░░░░░░░░░░░░░░   09.42 % 
🌃 Evening                402 commits         █████████░░░░░░░░░░░░░░░░   37.50 % 
🌙 Night                  525 commits         ████████████░░░░░░░░░░░░░   48.97 % 
```
📅 **I'm Most Productive on Tuesday** 

```text
Monday                   206 commits         █████░░░░░░░░░░░░░░░░░░░░   19.22 % 
Tuesday                  376 commits         █████████░░░░░░░░░░░░░░░░   35.07 % 
Wednesday                139 commits         ███░░░░░░░░░░░░░░░░░░░░░░   12.97 % 
Thursday                 37 commits          █░░░░░░░░░░░░░░░░░░░░░░░░   03.45 % 
Friday                   46 commits          █░░░░░░░░░░░░░░░░░░░░░░░░   04.29 % 
Saturday                 47 commits          █░░░░░░░░░░░░░░░░░░░░░░░░   04.38 % 
Sunday                   221 commits         █████░░░░░░░░░░░░░░░░░░░░   20.62 % 
```


📊 **This Week I Spent My Time On** 

```text
💬 Programming Languages: 
No Activity Tracked This Week

🔥 Editors: 
No Activity Tracked This Week

💻 Operating System: 
No Activity Tracked This Week
```


 Last Updated on 31/03/2026 12:10:01 UTC
<!--END_SECTION:waka-->

---

## Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=prabhavbansal27&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D&background=00000000&stroke=58A6FF&ring=e07a5f&fire=e07a5f&currStreakLabel=58A6FF&sideLabels=58A6FF&dates=8b949e" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=prabhavbansal27&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Activity" width="95%"/>
</p>

---

## Contributions

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/prabhavbansal27/prabhavbansal27/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/prabhavbansal27/prabhavbansal27/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/prabhavbansal27/prabhavbansal27/output/github-contribution-grid-snake.svg" width="98%" />
</picture>
</p>

---

## Connect

[![Portfolio](https://img.shields.io/badge/3D_Portfolio-prabhavbansal27.github.io-e07a5f?style=for-the-badge&logo=googlechrome&logoColor=white)](https://prabhavbansal27.github.io)
[![Nayikala](https://img.shields.io/badge/Founding-nayikala.com-10b981?style=for-the-badge&logo=googlechrome&logoColor=white)](https://nayikala.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-prabhav--bansal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/prabhav-bansal)
[![Email](https://img.shields.io/badge/Email-prabhav.bansal.27%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prabhav.bansal.27@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,12,20,24&height=100&section=footer" width="100%"/>
