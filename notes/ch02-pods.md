# Chapter 2 – Pods and Deployments

## Goals
- Understand what a Pod is
- Deploy NGINX using a Deployment manifest

## Steps
```bash
kubectl apply -f ch02/nginx-deployment.yaml
kubectl get pods
kubectl describe deployment nginx-deployment

