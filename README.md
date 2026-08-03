# Infrastructure-Monitoring-Lab

## Overview

This project implements an enterprise monitoring platform using:

- Ubuntu Server 24.04 LTS
- Prometheus
- Grafana
- Node Exporter

The solution provides centralized monitoring of:

- CPU Utilization
- Memory Usage
- Disk Usage
- Service Availability

Alerts are generated when system resources exceed defined thresholds.

---

## Architecture



Ubuntu Server
│
├── Grafana
├── Prometheus
└── Node Exporter

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Ubuntu Server | Operating System |
| Prometheus | Metrics Collection |
| Grafana | Visualization |
| Node Exporter | System Metrics |
| UFW | Firewall |

---

## Features

CPU Monitoring

Memory Monitoring

Disk Monitoring

Service Health Monitoring

Alerting

Dashboards

Historical Metrics

---

## Alert Thresholds

CPU Warning: >70%

CPU Critical: >90%

Memory Warning: >75%

Memory Critical: >90%

Disk Warning: >80%

Disk Critical: >95%

---

## Dashboards

### Infrastructure Dashboard

Displays:

- CPU Usage
- RAM Consumption
- Disk Utilization
- System Load

### Executive Dashboard

Displays:

- Availability
- Resource Trends
- Active Alerts
- Infrastructure Health

---

## Screenshots

[Grafana Screenshot

[Prometheus Targets Screenshot]

---

## Installation

See: docs/installation-guide.md

---

## Author
Ryan Jackson
