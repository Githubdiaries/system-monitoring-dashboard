# System Performance Monitoring Dashboard

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
![Grafana](https://img.shields.io/badge/Grafana-FF4D4F?logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

**One-command, production-ready system monitoring dashboard that actually looks beautiful.**

Built for:
- DevOps beginners who want to learn Grafana properly
- Developers & small teams who need real monitoring in < 5 minutes
- Companies looking for a clean, self-hosted observability starter

### Why this repo stands out
- Full working stack (not just a JSON file)
- Modern Grafana dashboard with clean thresholds, legends & time-series
- Zero-config docker-compose (just `docker compose up -d`)
- Ready for production (add alerts, scale, cloud in 2 minutes)

### Live Demo (add after you deploy)
→ [Live Dashboard](your-link-here)  *(deploy on Railway / Render / AWS free tier and put link here)*

### Dashboard Preview
*(Add 3-4 high-quality screenshots here – see Step 5)*

### Features
- Real-time CPU & Memory usage with color-coded thresholds
- Smooth Grafana time-series panels (dark theme, professional look)
- Fully containerized (Prometheus + Node Exporter + Grafana)
- Exportable & importable dashboard.json
- Easy to extend (disk, network, alerts coming soon)

### Tech Stack (Grafana-native)
- Grafana (latest)
- Prometheus
- Node Exporter
- Docker + Docker Compose

### One-Command Setup
```bash
git clone https://github.com/Githubdiaries/system-monitoring-dashboard.git
cd system-monitoring-dashboard
docker compose up -d
