# prometheus-stack

Docker compose for the Prometheus monitoring stack

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
