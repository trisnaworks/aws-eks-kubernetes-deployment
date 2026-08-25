# Kubernetes Deployment on Amazon EKS

This project deploys a real backend service on a managed Kubernetes cluster using Amazon EKS. It covers the full path from a Docker image to a running, network reachable Kubernetes Service.

## What This Project Does

- Explains how application code becomes a Docker image
- Shows how Kubernetes pulls that image from a registry
- Deploys the app using a Kubernetes Deployment, which manages Pods
- Exposes the app using a Kubernetes Service, so it can be reached over the network
- Shows how AWS networking and security groups interact with a Kubernetes cluster

The application includes API endpoints, a health check, and a simple UI so the running app can be checked visually, not just through the terminal.
