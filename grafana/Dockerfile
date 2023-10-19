# Dockerfile-grafana
FROM grafana/grafana
LABEL service="grafana"

# Copy the Grafana configuration files into the image
COPY ./grafana/datasources.yml /etc/grafana/provisioning/datasources/datasources.yml
COPY ./grafana/dashboards.yml /etc/grafana/provisioning/dashboards/dashboards.yml
COPY ./grafana/dbs /etc/grafana/provisioning/dashboards