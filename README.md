## Prerequisites:

1. minikube
2. kubectl

## How to Deploy?

```
minikube start
kubectl apply -f namespace.yaml
kubectl apply -f cron.yaml
kubectl apply -f node-exporter.yaml
```

## How to Verify?

```
ssh minikube
cd /data/metric
cat <file_name>
```