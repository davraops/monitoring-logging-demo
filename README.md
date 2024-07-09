# Monitoring and Logging Demo

This repository contains a demo setup for Prometheus and Grafana to monitor an application and infrastructure, as well as the ELK stack for centralized logging.

## Prometheus and Grafana

### Setup

1. Navigate to the `prometheus-grafana` directory:
    ```sh
    cd prometheus-grafana
    ```

2. Start Prometheus and Grafana using Docker Compose:
    ```sh
    docker-compose up -d
    ```

### Prometheus Configuration

Prometheus configuration is located in `prometheus/prometheus.yml`.

### Grafana Configuration

Grafana can be accessed at `http://localhost:3000` with default login credentials (`admin/admin`).

## ELK Stack

### Setup

1. Navigate to the `elk` directory:
    ```sh
    cd elk
    ```

2. Start the ELK stack using Docker Compose:
    ```sh
    docker-compose up -d
    ```

### Logstash Configuration

Logstash configuration is located in `logstash/logstash.conf`.

### Elasticsearch and Kibana

Elasticsearch can be accessed at `http://localhost:9200` and Kibana can be accessed at `http://localhost:5601`.
