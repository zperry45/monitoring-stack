### Internal Project Notes
### Single Server:

### Current containers used in monitroring stack:
- grafana: docker.io/grafana/grafana:6.7.4
- node exporter: docker.io/prom/node-exporter:v1.4.0
- prometheus: docker.io/prom/prometheus:v2.7.2
- alertmanager: docker.io/prom/alertmanager:v0.16.2
- zfs_Exporter: docker.io/45drives/zfs_exporter:v2.2.5
- znapzend_exporter: docker.io/ccremer/znapzend-exporter:v0.3.1

### Ports Used:
- grafana: 3000
- node exporter: 9100
- prometheus: 9091
- alertmanager: 9093
- zfs_exporter: 9134
- znapzend_exporter: 9101

### Random Notes:
- To access more info on the containers go to hub.docker.com and search for things like 45drives to find the zfs_exporter

