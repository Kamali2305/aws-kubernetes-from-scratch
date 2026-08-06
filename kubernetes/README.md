# Kubernetes Manifests

This folder contains the Kubernetes manifests used to deploy the application.

| File | Purpose |
|------|---------|
| deployment.yaml | Creates and manages the Nginx Pods. |
| service.yaml | Provides a stable network endpoint for the Pods. |
| configmap.yaml | Stores non-sensitive application configuration. |
| secret.yaml | Stores sensitive application configuration (demo password). |

Apply the manifests in this order:

```bash
kubectl apply -f configmap.yaml
kubectl apply -f secret.yaml
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```
