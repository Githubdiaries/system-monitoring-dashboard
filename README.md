# 📊 System Performance Monitoring Dashboard

A real-time system monitoring dashboard built using **Prometheus** and **Grafana**, visualizing key performance metrics like CPU and Memory usage.

---

## 🚀 Features

* 📈 Real-time **CPU Usage (%)**
* 🧠 Real-time **Memory Usage (%)**
* ⚡ Smooth time-series visualization
* 🔍 Powered by Prometheus metrics scraping
* 🎯 Clean and minimal Grafana dashboard design

---

## 🛠️ Tech Stack

* **Grafana** – Visualization & dashboards
* **Prometheus** – Metrics collection & monitoring
* **Node Exporter** – System-level metrics
* **Docker** – Containerized setup

---

## 📂 Project Structure

```
system-monitoring-dashboard/
│
├── dashboard.json       # Exported Grafana dashboard
├── README.md            # Project documentation
```

---

## ⚙️ Setup Instructions

### 1. Run Prometheus

```bash
docker run -d -p 9090:9090 --name prometheus prom/prometheus
```

---

### 2. Run Node Exporter

```bash
docker run -d -p 9100:9100 prom/node-exporter
```

---

### 3. Run Grafana

```bash
docker run -d -p 3000:3000 --name grafana grafana/grafana
```

---

### 4. Configure Grafana

* Open: http://localhost:3000
* Add Prometheus as data source
* Import `dashboard.json`

---

## 📊 Dashboard Preview

Displays:

* CPU Usage (%)
* Memory Usage (%)

---

## 🎯 Learning Outcome

* Hands-on with **monitoring systems**
* Understanding of **Prometheus metrics**
* Experience with **Grafana dashboards**
* Basic **DevOps workflow using Docker**

---

## 📌 Future Improvements

* Add Disk usage monitoring
* Add Alerts (CPU threshold, Memory spikes)
* Deploy on cloud (AWS / GCP)
* Add authentication & sharing

---

## 👩‍💻 Author

**Aksa Susan Abraham**

---

## ⭐ If you like this project

Do give it a ⭐
