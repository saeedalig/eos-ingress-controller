# Ingress Controller

Apply the Manifest
```
kubectl apply -f ingress.yaml
```

Verify the Deployment
```
kubectl get ns
kubectl get -n ingress-nginx pods
kubectl get -n ingress-nginx services
kubectl get ingresses
```