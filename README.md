# System Performance Monitoring Dashboard

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Grafana](https://img.shields.io/badge/Grafana-%23FF4D4F.svg?logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C.svg?logo=prometheus&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?logo=docker&logoColor=white)

**A clean, production-ready, one-command system monitoring stack with beautiful Grafana dashboards.**

Built for DevOps learners, developers, and small teams who want real monitoring without complexity.

### Why This Repo?
- Fully working out-of-the-box (not just a dashboard JSON)
- Modern, professional Grafana panels with proper thresholds and dark theme
- Zero-config Prometheus + Node Exporter setup
- Easy to extend with alerts, more metrics, or multi-node
- Solves the common pain: "I want to learn Grafana properly but everything is broken or ugly"

### Features
- Real-time CPU, Memory, Disk, Load, and Network metrics
- Color-coded thresholds (green/yellow/red) for quick insights
- Smooth time-series visualizations
- Fully containerized with Docker Compose
- Clean, exportable `dashboard.json`

### Tech Stack
- **Grafana** (latest) — Beautiful dashboards
- **Prometheus** — Metrics collection
- **Node Exporter** — Host system metrics
- **Docker + Docker Compose** — One-command deployment

### Quick Start (Local)

```bash
git clone https://github.com/Githubdiaries/system-monitoring-dashboard.git
cd system-monitoring-dashboard
docker compose up -d
```
### Setup in Grafana:

Open http://localhost:3000 (default: admin / admin)
Add Prometheus data source → URL: http://prometheus:9090
Import dashboard → Upload dashboard.json
Done — production-grade monitoring ready.

### Project Structure


system-monitoring-dashboard/
├── docker-compose.yml          # Everything in one file
├── prometheus.yml              # Ready scrape config
├── dashboard.json              # Professional Grafana dashboard
├── screenshots/                # Visual proof
├── README.md
└── LICENSE


### Future Improvements (Roadmap)

Built-in alerting rules (CPU > 80% → Slack/email)
Disk I/O + detailed Network panels
Multi-node / Docker container monitoring
Loki + Promtail for logs (full observability stack)
Detailed setup guides for production

### Contributing
PRs welcome! Open an issue first for major changes. See CONTRIBUTING.md.
Made with ❤️ by Aksa Susan Abraham
