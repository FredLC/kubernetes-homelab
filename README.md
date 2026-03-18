# Kubernetes Homelab on Raspberry Pi

This project showcases a **self-hosted Kubernetes homelab**, designed to experiment with cloud-native technologies, GitOps workflows, and infrastructure automation on low-power hardware.

## Overview

Built a lightweight Kubernetes environment using:

- Raspberry Pi (single-node cluster)
- k3s (lightweight Kubernetes)
- Flux (GitOps)
- Prometheus and Grafana (monitoring)
- Cloudflare (secure access)

## Key Features

### Kubernetes Cluster
Deployed a k3s-based Kubernetes cluster optimized for ARM-based hardware.

### GitOps Workflow
Implemented Flux to manage application deployments declaratively.

### Monitoring & Observability
Installed Prometheus and Grafana to monitor cluster and application performance.

### Secure Remote Access
Used Cloudflare Tunnels to securely expose services without opening inbound ports.

### Automated Updates
Configured Renovate to automate container image updates.

## Outcome

- Built a **fully functional Kubernetes homelab**  
- Implemented **GitOps for continuous deployment**  
- Enabled **secure remote access to self-hosted services**  
- Created a platform for experimenting with **cloud-native and DevOps tools**

## Tech Stack

Kubernetes (k3s), Raspberry Pi, Flux, Prometheus, Grafana, Cloudflare, Renovate
