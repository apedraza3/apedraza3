# Hey, I'm Alex

Software engineer building full-stack applications, trading systems, and homelab infrastructure. Currently working as a Software Test Engineer while independently building and running production systems full-time on the side.

![Java](https://img.shields.io/badge/Java-17-ED8B00?logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.13-3776AB?logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?logo=typescript&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.5-6DB33F?logo=springboot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3.1-000000?logo=flask)
![React Native](https://img.shields.io/badge/React_Native-Expo-61DAFB?logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-WAL-003B57?logo=sqlite)

## What I'm Building

**[Atlas Ledger](https://atlasledger.studio)** — Full-stack personal finance platform with Plaid bank syncing, Stripe payments, budgeting, crypto tracking, and AI-powered insights. Spring Boot, React Native, MySQL, Docker, deployed via CI/CD to a self-hosted Proxmox VM. *(private repo — live product)*

**[Congress Trader](https://github.com/apedraza3/congress-trader)** — Automated stock trading bot that analyzes congressional STOCK Act filings through a 5-factor risk scoring engine and executes trades via Alpaca. Python, Flask, SQLite.

**[Mining Profitability](https://github.com/apedraza3/mining-profitability)** — Real-time crypto mining fleet manager tracking 9 miners across 3 locations with profit/loss analysis, solar offset calculations, and pool comparison tools. Python, Flask, Chart.js.

**[Electricity Dashboard](https://github.com/apedraza3/electricity-dashboard)** — IoT energy monitoring system pulling real-time data from SunPower solar inverters and Emporia smart meters, with tiered utility billing and demand charge tracking. Python, Flask, SQLite.

**[AI Hub](https://github.com/apedraza3/ai-hub)** — Self-hosted AI workspace with RAG-enabled document chat and project management, running on 4x NVIDIA V100 SXM2 GPUs with NVLink via Ollama. Python, Flask, ChromaDB.

**[Media Scanner](https://github.com/apedraza3/media-scanner)** — 4-layer malware scanner for Plex media libraries using magic byte validation, custom YARA rules, ClamAV signatures, and VirusTotal hash lookups. Python, Flask, Docker.

**[Privacy Scanner](https://github.com/apedraza3/privacy-scanner)** — Automated data broker monitoring and removal tool that scans 76+ brokers, sends CCPA deletion emails, and automates opt-out forms via Playwright. Python, Flask, Playwright.

**[Network Monitor](https://github.com/apedraza3/network-monitor)** — Network monitoring dashboard for UniFi controllers with client tracking, uptime monitoring, and periodic speed testing. Python, Flask, SQLite.

**[PC Hardener](https://github.com/apedraza3/pc-hardener)** — Windows 11 debloater and privacy hardening tool with a Tkinter GUI, two-tier remediation, and automatic registry backup/restore. Python, Tkinter.

## Tech Stack

**Languages:** Java, Python, JavaScript, TypeScript, SQL, HTML/CSS

**Backend:** Spring Boot, Flask, Gunicorn, REST APIs, JWT, OAuth 2.0

**Frontend:** JSP, React Native (Expo), Chart.js, Tkinter

**Data:** MySQL, SQLite, Flyway migrations, Hibernate, ChromaDB

**Infrastructure:** Docker, Docker Compose, Proxmox, Cloudflare Tunnels, GitHub Actions CI/CD, Nginx

**Integrations:** Plaid, Stripe, Firebase, Alpaca, CoinGecko, Etherscan, ClamAV, YARA, VirusTotal, Playwright, Ollama

**Hardware:** Proxmox hypervisor, 4x V100 SXM2 GPU cluster (NVLink), ZFS RAIDZ2 storage, solar-integrated mining fleet

## Infrastructure

Everything runs on self-hosted infrastructure — no cloud providers:

- **Proxmox cluster** with 4 VMs handling web apps, media, network services, and AI workloads
- **CI/CD pipeline** — GitHub Actions runs unit tests + Cypress E2E against the live site, then auto-deploys via self-hosted runner
- **ZFS RAIDZ2** backup system with automated daily snapshots
- **Cloudflare tunnel** for secure external access without port forwarding
- **4x V100 SXM2 GPU server** with NVLink for local LLM inference

## Contact

**Portfolio:** [atlasledger.studio](https://atlasledger.studio)
**LinkedIn:** [Alexander Pedraza](https://www.linkedin.com/in/alexander-pedraza-380849251/)
**Email:** alex.pedraza761@gmail.com
