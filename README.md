
# Performance Monitoring Demo

This repository demonstrates setting up a performance testing and monitoring system using **JMeter**, **Grafana**, and **Docker**.

## Features
- Load testing using JMeter.
- Real-time monitoring with Grafana and Prometheus.
- Automated setup using Docker Compose.

---

## How to Use
1. Clone the repository.
2. Install Docker and Docker Compose.
3. Run `docker-compose up --build` to start all services.
4. Access Grafana at `http://localhost:3000` (default login: admin/admin).

5. Once everything is running, you can access Grafana at http://localhost:3000 (default login: admin / admin).
6. Configure the Prometheus data source in Grafana by going to Configuration > Data Sources and setting the URL to 
        http://prometheus:9090.
7. Create Grafana dashboards to visualize performance metrics (attached sample dashboard.json) (e.g., response times, error rates).
---

## Tools and Technologies
- **JMeter**: For performance testing.
- **Grafana & Prometheus**: For monitoring and visualization.
- **Docker**: For containerized setup.

---

