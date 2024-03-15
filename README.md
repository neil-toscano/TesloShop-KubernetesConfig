<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://cdn.icon-icons.com/icons2/2699/PNG/512/kubernetes_logo_icon_168359.png" width="200" alt="Nest Logo" /></a>
</p>

## inicializar minikube
```
    minikube start
```

## Revisar el estado de kubernetes
```
    kubectl get all
```

## Para los secretos de BACKEND, pgAdmin...etc
```
    kubectl apply -f backend-secrets.yml
```
## para el backend.yml ...etc
```
    kubectl apply -f backend.yml
```
## revisar logs tanto para pods, services...etcm
```
    kubectl describe deployment.apps/backend-deployment 
```

## Para revisar el backend
```
    minikube service backend-service 
```