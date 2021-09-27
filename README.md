# Hands-On-Kubernetes-on-Azure---Second-Edition
Hands-On Kubernetes on Azure - Second Edition


### Installing Cert manager

kubectl apply -f https://github.com/jetstack/cert-manager/releases/download/v1.5.3/cert-manager.yaml

### Service Catalog chart
```bash
$ kubectl create namespace catalog
$ helm repo add svc-cat https://kubernetes-sigs.github.io/service-catalog
$ helm install catalog svc-cat/catalog --namespace catalog
```
