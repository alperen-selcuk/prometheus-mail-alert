# prometheus-mail-alert

this repo prometheus and grafana installation on kubernetes with kubernetes pod and node alerting.

```
kubectl apply -f custom-alerts.yaml

helm install prometheus prometheus-community/kube-prometheus-stack -n monitoring -f prometheus-stack-values.yaml
```

if you dont have storageclass you can use hostPath on worker node
