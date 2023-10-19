# Dockerfile-prometheus
FROM prom/prometheus
LABEL service="prometheus"

# Copy the Prometheus configuration file into the image
COPY ./configs/prometheus/prometheus.yml /etc/prometheus/prometheus.yml

# Specify the command to run Prometheus with the custom configuration file
CMD ["--config.file=/etc/prometheus/prometheus.yml"]
