FROM centos
COPY  prometheus-2.18.1.linux-amd64 /etc/prometheus
WORKDIR /etc/prometheus/
CMD [ "--config.file=/etc/prometheus/prometheus.yml" ]
CMD exec ./prometheus
