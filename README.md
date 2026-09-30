<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Mohamed%20Ahmed&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Full%20Stack%20Engineer%20%7C%20API%20Architect%20%7C%20Builder&descAlignY=58&descSize=18&animation=fadeIn" />

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-ahmed-aa2b09288/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://moe-portfolio.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KiritoBloom)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamedahmedelsaadi@gmail.com)

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=A78BFA&center=true&vCenter=true&width=760&lines=Rust+%2B+Model+Context+Protocol+for+AI+agents+%E2%9A%A1;APIs+that+serve+400%2B+students+and+500%2B+downloads;React+%2F+Next.js+%2F+Flask+%2F+Rust+%2F+Redis+%2F+MongoDB;Based+in+Cairo+%F0%9F%87%AA%F0%9F%87%AC+%7C+Open+to+remote+work" alt="Typing SVG" />

</div>

---

## `whoami`

```python
class MohamedAhmed:
    role        = "Full Stack Developer & API Engineer"
    location    = "Cairo, Egypt"
    university  = "German University in Cairo - CS&E (2024-2029)"
    deployed    = "UniSight: 400+ students, 500+ Google Play downloads"
    shipped     = "WinKit: 51 read-only MCP tools for AI agents on Windows"
    languages   = ["English", "Arabic", "Korean", "German"]

    interests   = [
        "Systems and low level engineering",
        "Model Context Protocol and agent tooling",
        "API design and reverse engineering",
        "Developer experience and automation",
    ]

    currently   = "Building tools that make agents useful, not just busy."
```

---

## `stack`

<div align="center">

**Languages**

![Rust](https://img.shields.io/badge/Rust-E36C09?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**AI & Agent Tooling**

![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-A78BFA?style=flat-square&logo=anthropic&logoColor=white)
![Rust](https://img.shields.io/badge/MCP%20Servers-Rust-E36C09?style=flat-square&logo=rust&logoColor=white)
![JSON](https://img.shields.io/badge/JSON--RPC%202.0-8B949E?style=flat-square&logo=json&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & Data**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**DevOps & Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-CB3837?style=flat-square&logo=npm&logoColor=white)

</div>

---

## `projects`

<table>
<tr>
<td width="50%" valign="top">

### 01 · WinKit

> *Windows observability for AI agents.*

A read-only [Model Context Protocol](https://modelcontextprotocol.io) server in Rust that gives coding agents a permissioned, evidence-backed view of the Windows machine they run on. **51 tools**, all reads.

**Highlights**
- No cloud, no telemetry, no write / execute / delete paths anywhere
- Evidence-first diagnostics: separates `measured` from `interpreted`, with `confirmed` / `observed` / `possible` confidence
- Complete problem-solvers: `system_diagnose`, `crash_history`, `shutdown_analysis`, `diagnose_local_webapp`
- `WindowsBackend` trait with a mock backend, so the suite runs with no machine dependency
- One command registers the server and its companion agent skill in every installed client

**Stack:** `Rust` `MCP` `JSON-RPC 2.0` `Win32` `npm`

[![Source](https://img.shields.io/badge/Source-%23000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KiritoBloom/WinKit)

</td>
<td width="50%" valign="top">

### 02 · Campus Portal API Service

> *The API your university never built, so I did.*

Reverse-engineered an entire university portal into a production Python API used by **400+ students daily**, shipped as an Android app with **500+ Google Play downloads**.

**Highlights**
- Auth, schedules, grades, attendance and exam seating
- Redis caching, **10ms average response time**
- Admin panel with user management, cache control and API monitoring
- Interactive campus navigation with live directions
- GitHub Actions pipeline for real-time data sync

**Stack:** `Python` `Flask` `Redis` `Next.js` `GitHub Actions`

[![Live Showcase](https://img.shields.io/badge/Live%20Showcase-%23000000?style=for-the-badge&logo=vercel&logoColor=white)](https://unisight.vercel.app/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 03 · ProofChain API

> *Tamper-evident logs anyone can verify.*

Audit logging backend built on Merkle proofs and Ed25519 signing, so a third party can confirm a log was not rewritten after the fact.

**Highlights**
- Event ingestion with signed block sealing
- Transparency anchors for independent verification
- Standalone CLI verifier, no trust in the server required

**Stack:** `TypeScript` `Node.js` `MongoDB` `Ed25519`

[![Source](https://img.shields.io/badge/Source-%23000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KiritoBloom/ProofChain-API)

</td>
<td width="50%" valign="top">

### 04 · EcomControl Panel

> *Decoupled by design. Built to scale.*

A full headless e-commerce backend with RESTful APIs that lets any frontend plug in seamlessly, behind an admin control panel.

**Highlights**
- REST APIs supporting **multiple storefront integrations**
- Admin dashboard: products, pricing, analytics and inventory
- Secure JWT authentication flow
- Decoupled architecture for interchangeable frontend clients

**Stack:** `Next.js` `TypeScript` `MongoDB` `REST APIs`

[![Live Demo](https://img.shields.io/badge/Live%20Demo-%23000000?style=for-the-badge&logo=vercel&logoColor=white)](https://ecommerce-adminpage.vercel.app/)

</td>
</tr>
</table>

---

## `experience`

**Full Stack Developer & API Engineer** · Self-Employed · `July 2022 - Present`

- Built **WinKit** in Rust, a read-only MCP server with 51 tools that lets AI agents answer real questions about a Windows machine instead of guessing
- Published it to npm with a single-command installer for 9 coding agents, plus timestamped config backups
- Co-developed **UniSight**, serving 400+ students with 500+ Google Play downloads on a Redis-cached Flask API at 10ms response time
- Built **EcomControl Panel**, a headless e-commerce backend and admin panel with public and private REST APIs
- Automated data pipelines and deployments with GitHub Actions and Vercel

---

## `education`

**B.Sc. Computer Science & Engineering**
German University in Cairo (GUC) · `Nov 2024 - Nov 2029`

---

## `stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=KiritoBloom&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&title_color=A78BFA&icon_color=A78BFA&text_color=c9d1d9&bg_color=0d1117" height="170" alt="GitHub Stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KiritoBloom&layout=compact&theme=tokyonight&hide_border=true&title_color=A78BFA&text_color=c9d1d9&bg_color=0d1117&langs_count=8" height="170" alt="Top Languages"/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=KiritoBloom&theme=tokyonight&hide_border=true&background=0d1117&stroke=A78BFA&ring=A78BFA&fire=ff6b6b&currStreakLabel=A78BFA" alt="GitHub Streak" />

</div>

---

## `languages`

| Language | Proficiency |
|----------|-------------|
| English | Fluent |
| Arabic  | Native |
| Korean  | Conversational |
| German  | Conversational |

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&animation=fadeIn" />

**Thanks for stopping by. Let's build something great.**
[mohamedahmedelsaadi@gmail.com](mailto:mohamedahmedelsaadi@gmail.com) · [moe-portfolio.vercel.app](https://moe-portfolio.vercel.app)

</div>
