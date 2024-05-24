# Host Monitor

This project allows you to monitor the host's CPU, memory, and other metrics in real-time simply and effectively.

## Stack

- Telegraf
- InfluxDB
- Grafana

## How to run

1. Clone the repository:
   ```bash
   git clone <repository-URL>
   cd host-monitor 
   ```
2. Start the services with Docker Compose:
   ```bash
   docker compose up
   ```

## Access the metrics in real time

- Telegraf: [http://<host-ip>:9273/metrics](http://<host-ip>:9273/metrics)
- InfluxDB: [http://<host-ip>:8086](http://<host-ip>:8086)
- Grafana: [http://<host-ip>:3000](http://<host-ip>:3000)

## Examples

- Telegraf response on port 9273: [telegraf-metrics.txt](./telegraf-metrics.txt)
- Grafana dashboard queries: [grafana-querys.txt](./grafana-querys.txt)

