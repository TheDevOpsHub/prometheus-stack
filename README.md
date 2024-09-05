# prometheus-stack

Docker compose for the Prometheus monitoring stack

## Architecture

Doc: https://prometheus.io/docs/introduction/overview/
![architecture](https://prometheus.io/assets/architecture.png)

## Running the Stack

### Start the monitoring stack with:

```bash
docker-compose up -d
```

### Access the services:

- Prometheus: http://localhost:9090
- Grafana: http://localhost:3000 (default login: admin/admin)
- Alertmanager: http://localhost:9093
- cAdvisor: http://localhost:8080
- Node Exporter: http://localhost:9100

## Grafana dashboard

- https://grafana.com/grafana/dashboards/1860-node-exporter-full/
