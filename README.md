# 🚀 DockProm - Docker Monitoring Stack

A complete monitoring and observability solution for Docker hosts and containers using:

- Prometheus
- Grafana
- cAdvisor
- Node Exporter
- AlertManager
- Caddy

This setup helps you monitor server health, container performance, CPU usage, memory, storage, network traffic, and alerts — all in one place.

---

# 📌 Features

✅ Docker container monitoring  
✅ Real-time metrics visualization  
✅ Grafana dashboards pre-configured  
✅ Prometheus metrics collection  
✅ Alert management with AlertManager  
✅ Reverse proxy support using Caddy  
✅ Easy deployment with Docker Compose

---

# 🛠️ Tech Stack

| Tool | Purpose |
|------|----------|
| Prometheus | Metrics collection |
| Grafana | Visualization dashboards |
| cAdvisor | Container monitoring |
| Node Exporter | Host system metrics |
| AlertManager | Alert handling |
| Caddy | Reverse proxy & authentication |
| Docker Compose | Multi-container orchestration |

---

# 📂 Project Structure

```bash
dockprom/
│
├── prometheus/
├── grafana/
├── alertmanager/
├── cadvisor/
├── caddy/
├── docker-compose.yml
└── README.md
