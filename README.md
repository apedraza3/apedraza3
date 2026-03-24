# Hey, I'm Alex

Software engineer building full-stack applications, trading systems, and homelab infrastructure. Currently transitioning from test engineering into development — most of what you see here are production systems I built and run myself.

## What I'm Working On

**[Atlas Ledger](https://atlasledger.studio)** — Full-stack personal finance platform with bank syncing, budgeting, crypto tracking, and AI-powered insights. Spring Boot, React Native, MySQL, Docker, deployed via CI/CD pipeline to a self-hosted Proxmox VM.

**[Congress Trader](https://github.com/apedraza3/congress-trader)** — Automated stock trading bot that analyzes congressional STOCK Act filings through a multi-factor risk scoring engine and executes trades via Alpaca. Python, Flask, SQLite.

**[Mining Profitability Dashboard](https://github.com/apedraza3/mining-profitability)** — Real-time crypto mining fleet manager tracking 9 miners across 3 locations with profit/loss analysis, solar offset calculations, and pool comparison tools. Python, Flask, Chart.js.

**[Electricity Dashboard](https://github.com/apedraza3/electricity-dashboard)** — IoT-based energy monitoring system pulling real-time data from solar inverters and smart meters, calculating consumption, solar savings, and demand charges. Python, Flask, SQLite.

**[AI Hub](https://github.com/apedraza3/ai-hub)** — Local AI inference platform running on 4x NVIDIA V100 SXM2 GPUs with NVLink, serving models through Ollama and vLLM with a unified web interface. Python, Flask, ChromaDB.

## Tech Stack

**Languages:** Java, Python, JavaScript, SQL, HTML/CSS

**Backend:** Spring Boot, Flask, Gunicorn, REST APIs, JWT, OAuth 2.0

**Frontend:** JSP, React Native (Expo), Chart.js, responsive CSS

**Data:** MySQL, SQLite, Flyway migrations, Hibernate

**Infrastructure:** Docker, Docker Compose, Proxmox, Cloudflare Tunnels, GitHub Actions CI/CD, Nginx

**Integrations:** Plaid, Stripe, Firebase, Alpaca, CoinGecko, Etherscan, Expo Push API

**Hardware:** Proxmox hypervisor, 4x V100 SXM2 GPU cluster, ZFS RAIDZ2 storage, solar-integrated mining fleet

## Infrastructure

Everything runs on self-hosted infrastructure — no cloud providers:

- **Proxmox cluster** with 4 VMs handling web apps, media, network services, and AI workloads
- **CI/CD pipeline** — GitHub Actions runs unit tests + Cypress E2E against the live site, then auto-deploys via self-hosted runner
- **ZFS RAIDZ2** backup system with automated daily snapshots
- **Cloudflare tunnel** for secure external access without port forwarding

## Contact

**Portfolio:** [atlasledger.studio](https://atlasledger.studio)
