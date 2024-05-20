# Host monitor
This will allow you to monitor the host CPU, MEM and other metrics in real time simply and effectively.

# Stack
Telegraf, Influxdb and Grafana.

## How to run
```bash
# clone repository
cd host-monitor
docker compose up
```

## Access the metrics in real time
http://<ip-do-host>:9273/metrics    (Telegraf)  
http://<ip-do-host>:8086            (Influxdb)  
http://<ip-do-host>:3000            (Grafana)  

## Examples
Telegraf response from port 9273    (telegraf-metrics.txt)
Grafana dashboard querys            (grafana-querys.txt)