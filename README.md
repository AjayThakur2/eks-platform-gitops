# EKS Platform GitOps Repository

This repository contains Kubernetes desired state managed by ArgoCD.

## Architecture

Terraform:
- AWS Infrastructure
- EKS Cluster

ArgoCD:
- Kubernetes workloads
- Monitoring stack
- Applications

## Components

- ArgoCD
- Prometheus
- Grafana
- Alertmanager
- Helm based deployments

