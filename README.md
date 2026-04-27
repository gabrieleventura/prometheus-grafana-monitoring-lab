# Prometheus + Grafana Monitoring Lab

![Monitoring](https://img.shields.io/badge/Monitoring-Prometheus-orange)
![Dashboards](https://img.shields.io/badge/Dashboards-Grafana-F46800)
![Exporters](https://img.shields.io/badge/Metrics-Node_Exporter-green)
![Containers](https://img.shields.io/badge/Containers-Docker-blue)
![Proxy](https://img.shields.io/badge/Web-Nginx-brightgreen)
![Cloud](https://img.shields.io/badge/Cloud-Hetzner-red)
![OS](https://img.shields.io/badge/OS-Ubuntu_24.04-E95420)
![Security](https://img.shields.io/badge/Security-HTTPS-success)

Hands-on observability project deployed on Ubuntu VPS using Docker, Prometheus and Grafana.

---

## Public HTTPS Endpoint

Grafana deployed behind Nginx reverse proxy (authentication required).

🔗 https://grafana-lab.cervelliesplosi.com

## GitHub Repository

🔗 https://github.com/gabrieleventura/prometheus-grafana-monitoring-lab

## LinkedIn

🔗 https://www.linkedin.com/in/gabriele-ventura-6b549829b/

---

## Objective

Deploy a full monitoring stack using containers and expose dashboards securely over HTTPS.

---

## Stack

- Prometheus
- Grafana
- Node Exporter
- cAdvisor
- Docker Compose
- Nginx reverse proxy
- Let's Encrypt
- Ubuntu 24.04

---

## What I Implemented

- Real-time Linux server monitoring
- Docker container metrics collection
- Public HTTPS Grafana exposure
- Reverse proxy with Nginx
- Prometheus datasource integration
- Dashboard deployment and configuration
- External DNS + TLS setup

---

## Screenshots

### Grafana Dashboard

![Dashboard](screenshots/grafana-dashboard.png)

### Live Metrics Under Load

![Metrics](screenshots/grafana-metrics.png)

---

## Key Learning

Deploying services is one thing.

Understanding system behaviour in production is another.

Monitoring transforms infrastructure into something visible, measurable and improvable.

---

## Skills Demonstrated

- Linux Administration
- Docker Operations
- Monitoring & Observability
- Metrics Pipelines
- Reverse Proxying
- HTTPS / TLS
- Troubleshooting
- Production Thinking
