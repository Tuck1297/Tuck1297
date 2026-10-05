<div align="center">
  <h1>Tucker Johnson</h1>
  <p><em>Frontend Software Developer &nbsp;|&nbsp; MS Software Engineering · University of St. Thomas</em></p>
</div>

<div align="center">
  <img src="https://github.com/Tuck1297/tuck1297.github.io/blob/master/Media/Code-Inspiration-Yellowstone.jpg" width="600" alt="Code inspiration — Yellowstone"/>
  <br/><br/>
  <a href="https://tuckerjohnson.me"><img src="https://img.shields.io/badge/Portfolio-tuckerjohnson.me-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio Website"/></a>
  <a href="https://www.linkedin.com/in/johnson-tucker-dev/"><img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://www.instagram.com/humble4realphotos/"><img src="https://img.shields.io/badge/Photography-Instagram-E1306C?style=for-the-badge&logo=instagram&logoColor=white" alt="Photography Instagram"/></a>
</div>

---

## 👋 About Me

I'm a frontend developer building production UI in **React, TypeScript, and Mantine**. I'm also finishing a **Master of Science in Software Engineering** at the University of St. Thomas.

I like work where a clean interface sits on top of a real system, so most of my side projects run end to end: data ingestion, an API, a database, and the UI on top. I also lean heavily on AI-assisted development and build my own tooling around it.

---

## 🚀 Featured Projects

The source for these projects is private, but I'm happy to walk through the code and architecture of any of them. Where something is live, it's linked.

### 🌐 [tuckerjohnson.me](https://tuckerjohnson.me) — my personal platform
Started as a portfolio and grew into my main playground: **740+ commits** in a **pnpm monorepo** of about 20 workspace packages, built on **Next.js 16, React 19, Mantine 9, and Tailwind 4**.

**Public, live on the site:**
- 🛠️ **[Tools](https://tuckerjohnson.me/tools)** — 17 free, client-side developer tools: SQL formatter, diff checker, Mermaid renderer, PDF tools, JSON ↔ CSV, EML viewer, DOM tree visualizer, code-to-image, and more
- 🧩 **[Artifacts](https://tuckerjohnson.me/artifacts)** — 30+ UI prototypes: dispatch boards, scheduling and capacity views, KPI scorecards, work-order pipelines, form and table patterns
- 🎨 **[Creative](https://tuckerjohnson.me/creative)** — Three.js scenes, generative canvas art, and small games
- 🚝 **[Walt Disney World transportation map](https://tuckerjohnson.me/disney-map)** — a Leaflet map of the monorail, Skyliner, boat, and bus networks

**Private side:**
- A signed-in **dashboard**: Kanban board, knowledge base, finances, reading and watch lists, and system logs
- Built-in **Gantt chart, spreadsheet, rich-text editor, and report-builder** packages
- A **.NET API** behind all of it, with **Azure Functions** for scheduled jobs (status emails and data sync)
- An **offline-first Flutter app** that syncs with the same API
- An **MCP server** that lets AI assistants read and prioritize the Kanban board

`Next.js` `React` `TypeScript` `Mantine` `Tailwind` `Three.js` `C#` `.NET` `Azure Functions` `Flutter` `MCP`

### 🎢 Queuenaut — *in active development*
A Walt Disney World companion app for ride wait times, downtime prediction, and a lifetime "park passport."
A local-first **Flutter** client sits on a private telemetry pipeline: **n8n** ingests live park data every 5 minutes into **CockroachDB**, and a **C# (.NET 10) Minimal API** serves historical downtime distributions through a **Cloudflare Tunnel**. A **Next.js** dashboard handles telemetry and insights.

`Flutter` `Dart` `C#` `.NET 10` `CockroachDB` `n8n` `Docker` `Next.js`

### 🌲 Explore More — *rebuilding*
An interactive map that pulls Minnesota's outdoor recreation data (state parks, campgrounds, trails) into one searchable platform.
The first version was built on **Leaflet** and **OpenLayers**. It's now being rebuilt in **Next.js** on a **PostgreSQL** schema, with **n8n** workflows handling data collection and sync.

`TypeScript` `Next.js` `Leaflet` `OpenLayers` `PostgreSQL` `n8n`

### 🖥️ Scripts Toolkit — a terminal launcher for my automation
I got tired of remembering flags, so I built a **keyboard-first terminal UI (Python, Textual)** that runs all my scripts from one place.
Each script registers itself with a small **YAML manifest**. The TUI finds it automatically, builds an input form from the manifest's arguments (file pickers, toggles, text fields), and streams the output live. Adding a script needs no UI code.

A few of the scripts it runs:
- **FFmpeg templates:** a dozen parameterized recipes for cropping, reversing, converting, frame extraction, and batch WebP conversion
- **Media Validator:** recursively scans folders for corrupt images, video, and audio
- **OpenAPI → TypeScript:** generates types from a spec file or URL and opens the result in VS Code
- **Markdown → PDF:** renders Markdown to PDF through a Gotenberg (headless Chromium) service
- **Google Chat Transcriber:** turns Google Takeout chat exports into formatted Word documents with embedded images

`Python` `Textual` `YAML` `FFmpeg`

### 🧪 From my experiments lab
| Project | What it does | Built with |
| --- | --- | --- |
| **Disney Family Trivia** | A park-by-park trivia game for the family, at home or in the queue | Flutter |
| **Windows Setup & Sync** | Rebuilds my development environment on a new machine: clones repos, checks installed software, syncs settings | PowerShell |

---

## 🛠️ What I Work With

<div>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" title="React" alt="React" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" title="Next.js" alt="Next.js" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" title="C#" alt="C#" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dotnetcore/dotnetcore-original.svg" title=".NET" alt=".NET" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" title="Flutter" alt="Flutter" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" title="Node.js" alt="Node.js" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" title="PostgreSQL" alt="PostgreSQL" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" title="Docker" alt="Docker" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" title="Azure" alt="Azure" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" title="AWS" alt="AWS" width="45" height="45"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" title="Git" alt="Git" width="45" height="45"/>
</div>

**Also:** Python & Textual · Mantine UI · Tailwind · Three.js · Leaflet & OpenLayers · Azure Functions · n8n · CockroachDB · Cloudflare Tunnels · MCP · Claude Code & AI-assisted workflows

---

## 📚 Currently Working Toward

- 🎓 **MS Software Engineering**, University of St. Thomas: cloud architecture, databases, software design
- ☁️ **[AWS Certified Developer – Associate](https://aws.amazon.com/certification/certified-developer-associate/)**
- 🤖 **[Microsoft Certified: Azure AI Cloud Developer Associate (AI-200)](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-cloud-developer-associate/)**
- 🧠 **[Anthropic — AI Fluency for Builders](https://anthropic.skilljar.com/ai-fluency-for-builders)**

**Completed:** JPMorgan Chase Software Engineering Virtual Experience (Forage) · [Meta Front-End Developer Professional Certificate](https://www.coursera.org/professional-certificates/meta-front-end-developer)

---

## 📈 Activity

Most of my work happens in private repositories, which this card includes.

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=Tuck1297&theme=dark&background=000000)](https://git.io/streak-stats)

---

<div align="center">
  <sub>📍 Based in Minnesota &nbsp;|&nbsp; Open to connecting — <a href="https://www.linkedin.com/in/johnson-tucker-dev/">LinkedIn</a> · <a href="https://tuckerjohnson.me">tuckerjohnson.me</a></sub>
</div>
