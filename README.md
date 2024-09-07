# ClusterDeploy

## Overview

ClusterDeploy is a comprehensive project designed to showcase Kubernetes environment using K3s, a lightweight Kubernetes distribution. This project integrates various components essential for modern cloud-native applications, including ArgoCD for GitOps, Prometheus for monitoring, Grafana for visualization, Ingress-Nginx as the Ingress controller, and Kubeseal for secure secret management.

The Ingress resource is configured to use a TLS-Secret for handling HTTPS traffic, ensuring secure communication between clients and the services.

## Tools

- [K3s](https://k3s.io/)
- [Helm](https://helm.sh/)
- [Kubeseal](https://sealed-secrets.netlify.app/)
- [ArgoCD](https://argoproj.github.io/cd/)
- [Grafana](https://grafana.com/)
- [Prometheus](https://prometheus.io/)
- [Ingress-Nginx](https://kubernetes.github.io/ingress-nginx/)

## Architecture

![ClusterDeploy-Diagram](./assets/cluster-deploy.svg)
