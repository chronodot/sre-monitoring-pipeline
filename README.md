# SRE Monitoring Pipeline  
End-to-End Observability with Prometheus, Alertmanager, Grafana & Slack

## Overview
This project implements a **production-grade SRE monitoring pipeline**, bringing together the full monitoring and alerting lifecycle using:

- **Prometheus** – Metrics scraping & time-series database  
- **Node Exporter** – System-level metrics  
- **Alertmanager** – Alert routing & notifications  
- **Grafana** – Dashboards & visualizations  
- **Slack** – Real-time alerting channel  

The goal is to simulate a real-world observability setup used in modern SRE/DevOps environments for **infrastructure monitoring, alerting, reliability, and performance insights**.

---

## Features
- Full **Prometheus + Node Exporter** metrics pipeline  
- **Grafana dashboards** for CPU, Memory, Disk, Network, and Host metrics  
- **Alertmanager rules** with severity levels (warning/critical)  
- **Slack integrations** for instant alerting  
- Pre-configured alert rules for:
  - High CPU usage  
  - High memory usage  
  - Instance down  
  - Disk pressure  
  - Node unreachable  
- Runs **entirely using Docker Compose**  
- Clean folder structure for production deployments  

---
