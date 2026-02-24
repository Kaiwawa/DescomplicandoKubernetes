## Create cluster with kind
### 1 Control-Plane, 3 Workers
kind create cluster --config meuprimeirocluster.yaml --name meuprimeirocluster

## Create pod with kubectl
### Nginx
kubectl apply -f pod.yaml
