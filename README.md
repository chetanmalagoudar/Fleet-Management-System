# Fleet Management System

## Overview

This repository contains Kubernetes manifests for deploying the Fleet Management System application, supporting both development and production-grade deployments.

## Development-Grade Deployment

### Purpose

The development-grade deployment is intended for local development purposes. You can use these manifests to set up the Fleet Management System on your local environment without the need for cloud services or complex configurations.

## Production-Grade Deployment

### Purpose

The production-grade deployment is designed for deploying the Fleet Management System on a cloud provider such as AWS. It includes configurations for scalability, reliability, and production-level performance.

## Manifests Structure

- `workloads/`: Contains Deployment and Service manifests for the Fleet Management System application.
- `alerts/`: Configuration for alerting, including Slack alerts.
- `monitoring/`: Configuration for monitoring, such as Prometheus.
- `elk/`: Configuration for logging using Elasticsearch, Fluentd, and Kibana.

You can customize these manifests to suit your specific requirements.

## Monitoring and Logging

In production-grade deployments, we utilize the EFK (Elasticsearch, Fluentd, Kibana) stack for logging and Prometheus for monitoring. Adjust the configurations in the `production-grade/` directory as needed.

## Alerting

Alerts, including Slack alerts, are configured in the `manifests/alerts/` directory. Modify alerting rules and channels to meet your requirements.

