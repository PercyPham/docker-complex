# Start

## Install

- Docker
- Minikube
- Kubectl

## Run

Run minikube

```
minikube start
```

Run configs for kubernetes

```
kubectl apply -f k8s
```

Run ingress-nginx

```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-
nginx/master/deploy/static/mandatory.yaml

minikube addons enable ingress
```

## See result

Get IP address

```
minikube ip
```

Use that IP to browse on browser
