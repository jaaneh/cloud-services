# Dockerfile-grafana
FROM grafana/grafana
LABEL service="grafana"

# Copy the Grafana configuration files into the image
COPY ../configs/grafana/datasources.yml /etc/grafana/provisioning/datasources/datasources.yml
COPY ../configs/grafana/dashboards.yml /etc/grafana/provisioning/dashboards/dashboards.yml
COPY ../configs/grafana/dbs /etc/grafana/provisioning/dashboards