# k8s-demo

Basic Kubernetes example: an nginx Deployment (2 replicas) exposed by a NodePort Service.

## Deploy
```bash
kubectl apply -f k8s/
kubectl get pods
kubectl get svc
```

## Access (Minikube)
```bash
minikube service my-app-service
```

## Clean up
```bash
kubectl delete -f k8s/
```
