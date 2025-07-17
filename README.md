# observility-promithious
Prometheus is a powerful open-source monitoring and alerting toolkit designed for reliability and scalability—especially in dynamic, cloud-native environments like Kubernetes


**## Essential config files for Obsevability

Please create T2 instance from AWS
sudo apt update
sudo apt install docker.io
sudo apt install docker-commose-v2
sudo usermod -aG docker $USER && newgrp docker
mkdir ovserbility :: cd ovserbility
git clone http://github.com/ashis103/observability.git
cd observability
docker compose up - d
IP:9090 # promitheos site
Ip:8080 # CAadvisor**
rate(container_cpu_usage_secound_total{name="students-app"}[5m]) # Promitheous Query


**Download the prometheus config file**
wget https://raw.githubusercontent.com/prometheus/prometheus/main/documentation/examples/prometheus.yml**

**Download Loki Config**
wget https://raw.githubusercontent.com/grafana/loki/v2.8.0/cmd/loki/loki-local-config.yaml -O loki-config.yaml

**Download Promtail Config**
wget https://raw.githubusercontent.com/grafana/loki/v2.8.0/clients/cmd/promtail/promtail-docker-config.yaml -O promtail-config.yaml
