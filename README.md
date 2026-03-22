# Docker Monitoring Demo

This project demonstrates a basic monitoring setup using Docker, Prometheus, and Grafana.

## Overview

The application exposes metrics that are collected by Prometheus and visualized in Grafana.

## Tech Stack

- Docker
- Prometheus
- Grafana
- Python (Flask)

## Services

- App — Flask application with Prometheus metrics
- Prometheus — collects and stores metrics
- Grafana — visualizes metrics

## Run locally

docker compose up --build

## Endpoints

- App: http://localhost:5002
- Prometheus: http://localhost:9090
- Grafana: http://localhost:3000

## Notes

This project is intended for learning DevOps fundamentals including containerization and monitoring.
