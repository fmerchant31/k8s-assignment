# Kubernetes EKS Assignment

### Objective
This repository demonstrates:
- Amazon EKS setup  
- Kubernetes application deployment  
- Ingress configuration for external access  
- Horizontal Pod Autoscaler (HPA) based on memory utilization  
- Datadog integration for monitoring and alerts  

---

## Files Overview

### `deploy.yaml`
Deploys a sample Nginx application.

### `service.yaml`
Exposes the app internally via ClusterIP (or LoadBalancer if configured).

### `ingress.yaml`
Routes external HTTP traffic to the sample application.

### `hpa.yaml`
Configures Horizontal Pod Autoscaler (HPA) to scale the app based on memory usage.

### `datadog-values.yaml`
Helm configuration file for deploying Datadog agent on the cluster.

### `main.tf`
Example Terraform script to create an EKS cluster.

### `Documentation.pdf`
Full step-by-step guide for setting up the cluster, deploying the application, configuring Ingress, HPA, and integrating Datadog.
