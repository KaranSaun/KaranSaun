<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KaranSaun/github-brand-system/main/assets/banner.svg">
  <img src="https://raw.githubusercontent.com/KaranSaun/github-brand-system/main/assets/banner.svg" width="100%" alt="Karan Saun — AI Systems Engineer">
</picture>

---

<p align="center">
  <a href="https://github.com/KaranSaun/wms"><img src="https://img.shields.io/badge/NEXUS-Warehouse_Intel-00d4ff?style=for-the-badge&logo=github&labelColor=0a0e17" alt="NEXUS"></a>
  <a href="https://github.com/KaranSaun/TXLAYERS"><img src="https://img.shields.io/badge/TexLayerAI-Textile_AI-8b5cf6?style=for-the-badge&logo=github&labelColor=0a0e17" alt="TexLayerAI"></a>
  <a href="https://github.com/KaranSaun/quantara"><img src="https://img.shields.io/badge/APEX%20OS-AI_Trading-10b981?style=for-the-badge&logo=github&labelColor=0a0e17" alt="APEX OS"></a>
  <a href="https://github.com/KaranSaun/Sentiy-Market-Psychology-Narrative-Intelligence-Engine"><img src="https://img.shields.io/badge/Sentiy-Market_Psychology-f59e0b?style=for-the-badge&logo=github&labelColor=0a0e17" alt="Sentiy"></a>
</p>

---

<table>
  <tr>
    <td width="60%" valign="top">

## ▎About

I build **production AI systems** that automate complex real-world workflows.

Every project I ship is full-stack: AI backend, interactive dashboard, containerized deployment. My work spans **warehouse intelligence**, **manufacturing automation**, **financial trading**, and **market psychology** — the constant is AI-powered automation at production scale.

I don't stop at the model. I build the system.

    </td>
    <td width="40%" valign="top">

## ▎Current Mission

```
■ Building   → NEXUS Warehouse Intelligence
■ Building   → TexLayerAI Textile Automation  
■ Building   → APEX OS Trading Platform
■ Building   → Sentiy Market Psychology Engine

◆ Learning   → Distributed AI Systems
◆ Research   → Multi-agent Architectures

○ Exploring  → GPU Computing at Scale
○ Exploring  → Real-time ML Pipelines
```

    </td>
  </tr>
</table>

---

## ▎Engineering DNA

<table>
  <tr>
    <td width="25%" align="center">
      <img src="https://raw.githubusercontent.com/KaranSaun/github-brand-system/main/assets/icons/ai.svg" width="48" alt="AI"><br>
      <strong>AI Integration</strong><br>
      <sub>SAM2 · Real-ESRGAN · LLMs<br>Computer Vision · NLP</sub>
    </td>
    <td width="25%" align="center">
      <img src="https://raw.githubusercontent.com/KaranSaun/github-brand-system/main/assets/icons/fastapi.svg" width="48" alt="Backend"><br>
      <strong>Backend Systems</strong><br>
      <sub>FastAPI · Celery · PostgreSQL<br>Redis · WebSockets</sub>
    </td>
    <td width="25%" align="center">
      <img src="https://raw.githubusercontent.com/KaranSaun/github-brand-system/main/assets/icons/nextjs.svg" width="48" alt="Frontend"><br>
      <strong>Frontend Platforms</strong><br>
      <sub>Next.js · React · TailwindCSS<br>Recharts · Framer Motion</sub>
    </td>
    <td width="25%" align="center">
      <img src="https://raw.githubusercontent.com/KaranSaun/github-brand-system/main/assets/icons/docker.svg" width="48" alt="Infra"><br>
      <strong>Infrastructure</strong><br>
      <sub>Docker · Nginx · MinIO<br>CI/CD · Render</sub>
    </td>
  </tr>
</table>

---

## ▎Flagship Projects

<table>
  <tr>
    <th width="5%"></th>
    <th width="25%">Project</th>
    <th width="45%">What It Does</th>
    <th width="25%">Stack</th>
  </tr>
  <tr>
    <td align="center">01</td>
    <td><a href="https://github.com/KaranSaun/wms"><b>NEXUS</b></a><br><sub>Warehouse Intelligence</sub></td>
    <td>Automates WMS data extraction via browser automation, runs ETL pipelines, and delivers real-time operational analytics through an interactive command center. Replaces manual Excel workflows with an intelligent dashboard.</td>
    <td><sub>FastAPI · Next.js · Celery<br>PostgreSQL · Playwright<br>Docker · WebSockets</sub></td>
  </tr>
  <tr>
    <td align="center">02</td>
    <td><a href="https://github.com/KaranSaun/TXLAYERS"><b>TexLayerAI</b></a><br><sub>Textile Design Automation</sub></td>
    <td>Upload a textile design — AI upscales (Real-ESRGAN), segments motifs (SAM2), clusters colors (Delta-E CIE2000), and exports print-ready layered TIFFs with automated colorway variants. Replaces hours of manual Photoshop work.</td>
    <td><sub>FastAPI · Next.js · Celery<br>SAM2 · Real-ESRGAN · OpenCV<br>MinIO · Docker · JWT</sub></td>
  </tr>
  <tr>
    <td align="center">03</td>
    <td><a href="https://github.com/KaranSaun/quantara"><b>APEX OS</b></a><br><sub>AI Trading Platform</sub></td>
    <td>Personal AI command center for Indian retail options traders. Routes queries across 5+ AI providers with automatic fallback, analyzes NSE data in real-time, and delivers morning trade recommendations via Telegram.</td>
    <td><sub>FastAPI · Next.js · Supabase<br>Gemini · Claude · Groq<br>yfinance · Telegram · Docker</sub></td>
  </tr>
  <tr>
    <td align="center">04</td>
    <td><a href="https://github.com/KaranSaun/Sentiy-Market-Psychology-Narrative-Intelligence-Engine"><b>Sentiy</b></a><br><sub>Market Psychology Engine</sub></td>
    <td>Real-time market psychology and narrative intelligence. Ingests news, social media, and price data — applies NLP sentiment analysis, behavioral finance models, and crowd psychology signals to uncover <em>why</em> markets move.</td>
    <td><sub>FastAPI · Next.js · Celery<br>NLTK · VADER · yfinance<br>NewsAPI · Pandas · Docker</sub></td>
  </tr>
</table>

---

## ▎Architecture Overview

```
                        ┌──────────────────────┐
                        │    Nginx / Render     │
                        │   (Reverse Proxy)     │
                        └──────┬───────────┬────┘
                               │           │
                    ┌──────────▼──┐  ┌─────▼──────────┐
                    │   FastAPI   │  │  Next.js 14     │
                    │   Backend   │  │  Frontend       │
                    │  :8000      │  │  :3000          │
                    └──────┬──────┘  └─────────────────┘
                           │
              ┌────────────┼────────────┐
              │            │            │
       ┌──────▼───┐ ┌─────▼─────┐ ┌────▼─────┐
       │PostgreSQL│ │   Redis   │ │  MinIO   │
       │Database  │ │  Broker   │ │  Object  │
       │          │ │  + Cache  │ │  Storage │
       └──────────┘ └─────┬─────┘ └──────────┘
                          │
                   ┌──────▼──────┐
                   │   Celery    │
                   │   Worker    │
                   │  (AI Tasks) │
                   └─────────────┘
```

---

## ▎Technology Stack

<table>
  <tr>
    <td align="right" width="15%"><b>Languages</b></td>
    <td width="85%">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript">
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
      <img src="https://img.shields.io/badge/Shell-121011?style=flat&logo=gnu-bash&logoColor=white" alt="Shell">
    </td>
  </tr>
  <tr>
    <td align="right"><b>AI / ML</b></td>
    <td>
      <img src="https://img.shields.io/badge/SAM2-8B5CF6?style=flat&logo=meta&logoColor=white" alt="SAM2">
      <img src="https://img.shields.io/badge/Real--ESRGAN-00D4FF?style=flat&logo=opencv&logoColor=white" alt="Real-ESRGAN">
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" alt="scikit-learn">
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white" alt="OpenCV">
      <img src="https://img.shields.io/badge/NLTK-154F5C?style=flat&logo=python&logoColor=white" alt="NLTK">
      <img src="https://img.shields.io/badge/Pillow-3776AB?style=flat&logo=python&logoColor=white" alt="Pillow">
    </td>
  </tr>
  <tr>
    <td align="right"><b>Backend</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI">
      <img src="https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white" alt="Celery">
      <img src="https://img.shields.io/badge/SQLAlchemy-CC2927?style=flat&logo=python&logoColor=white" alt="SQLAlchemy">
      <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white" alt="Pydantic">
      <img src="https://img.shields.io/badge/Alembic-7F3FBF?style=flat&logo=python&logoColor=white" alt="Alembic">
    </td>
  </tr>
  <tr>
    <td align="right"><b>Frontend</b></td>
    <td>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white" alt="Next.js">
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" alt="React">
      <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwind-css&logoColor=white" alt="TailwindCSS">
      <img src="https://img.shields.io/badge/Zustand-443E38?style=flat&logo=react&logoColor=white" alt="Zustand">
      <img src="https://img.shields.io/badge/Framer-0055FF?style=flat&logo=framer&logoColor=white" alt="Framer Motion">
      <img src="https://img.shields.io/badge/Recharts-22B5BF?style=flat&logo=chartdotjs&logoColor=white" alt="Recharts">
    </td>
  </tr>
  <tr>
    <td align="right"><b>Database</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" alt="Redis">
      <img src="https://img.shields.io/badge/MinIO-C72E49?style=flat&logo=minio&logoColor=white" alt="MinIO">
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white" alt="Supabase">
    </td>
  </tr>
  <tr>
    <td align="right"><b>Infrastructure</b></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white" alt="Nginx">
      <img src="https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=white" alt="Render">
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white" alt="GitHub Actions">
      <img src="https://img.shields.io/badge/Playwright-45BA4B?style=flat&logo=playwright&logoColor=white" alt="Playwright">
    </td>
  </tr>
</table>

---

## ▎Engineering Dashboard

<table>
  <tr>
    <td align="center" width="25%">
      <img src="https://github-readme-stats.vercel.app/api?username=KaranSaun&show_icons=true&count_private=true&include_all_commits=true&hide_rank=true&hide_title=true&bg_color=0a0e17&title_color=00d4ff&text_color=94a3b8&icon_color=8b5cf6&border_color=151c2c&border_radius=12" width="100%">
    </td>
    <td align="center" width="25%">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KaranSaun&layout=compact&hide_title=true&langs_count=8&bg_color=0a0e17&title_color=00d4ff&text_color=94a3b8&icon_color=8b5cf6&border_color=151c2c&border_radius=12" width="100%">
    </td>
    <td align="center" width="25%">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=KaranSaun&hide_border=true&background=0a0e17&stroke=151c2c&ring=00d4ff&fire=00d4ff&currStreakNum=f0f4f8&sideNums=94a3b8&currStreakLabel=00d4ff&sideLabels=64748b&dates=475569" width="100%">
    </td>
    <td align="center" width="25%">
      <img src="https://github-profile-trophy.vercel.app/?username=KaranSaun&theme=darkhub&no-frame=true&no-bg=true&row=2&column=2&title=-Followers,-Stars,-Issues,-Reviews" width="100%">
    </td>
  </tr>
</table>

<details>
  <summary><b>▎Activity Graph</b></summary>
  <br>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=KaranSaun&bg_color=0a0e17&color=00d4ff&line=8b5cf6&point=00d4ff&area=true&area_color=00d4ff&hide_border=true&radius=12" width="100%">
</details>

<details>
  <summary><b>▎Contribution Grid</b></summary>
  <br>
  <img src="https://raw.githubusercontent.com/KaranSaun/KaranSaun/main/assets/github-contribution-grid-snake.svg" width="100%" alt="Snake animation">
</details>

---

## ▎Roadmap

```
Q3 2026  ■ NEXUS v2 — Multi-facility support, predictive analytics, AI insights
         ■ TexLayerAI — API productization, public demo, batch processing
         ■ APEX OS — Real-time execution alerts, backtesting engine
         ■ Sentiy — Real-time news pipeline, multi-source aggregation, Telegram bot

Q4 2026  ■ Sentiy — Predictive sentiment model, options flow integration, public dashboard
         ■ Distributed AI pipeline framework (open source)
         ■ Multi-agent orchestration system
         ■ GPU-accelerated inference serving

2027     ■ AI infrastructure platform
         ■ Real-time ML feature store
         ■ Production MLOps tooling
```

---

## ▎Connect

<p align="center">
  <a href="https://github.com/KaranSaun"><img src="https://img.shields.io/badge/GitHub-KaranSaun-0a0e17?style=for-the-badge&logo=github&logoColor=00d4ff&labelColor=0a0e17&borderColor=00d4ff" alt="GitHub"></a>
  <a href="https://github.com/KaranSaun/Sentiy-Market-Psychology-Narrative-Intelligence-Engine"><img src="https://img.shields.io/badge/Sentiy-Market_Psychology-f59e0b?style=for-the-badge&logo=github&labelColor=0a0e17" alt="Sentiy"></a>
  <a href="mailto:karan@example.com"><img src="https://img.shields.io/badge/Email-Contact-8b5cf6?style=for-the-badge&logo=maildotru&logoColor=8b5cf6&labelColor=0a0e17" alt="Email"></a>
  <a href="https://www.linkedin.com/in/karansaun/"><img src="https://img.shields.io/badge/LinkedIn-Profile-00d4ff?style=for-the-badge&logo=linkedin&logoColor=00d4ff&labelColor=0a0e17" alt="LinkedIn"></a>
</p>

---

<p align="center">
  <sub>Built with intention. Every system solves a real problem.</sub>
  <br>
  <sub>Profile last updated June 2026 · <a href="https://github.com/KaranSaun/github-brand-system">Brand System</a></sub>
  <br><br>
  <img src="https://komarev.com/ghpvc/?username=KaranSaun&color=00d4ff&style=flat-square&label=Visitors" alt="Visitors">
  <img src="https://img.shields.io/github/stars/KaranSaun?style=flat-square&color=8b5cf6&logo=github&label=Stars" alt="Stars">
  <img src="https://img.shields.io/github/followers/KaranSaun?style=flat-square&color=00d4ff&logo=github&label=Followers" alt="Followers">
</p>
