# Lesson 5 - Step 2

```sh
kubectl apply -n observability -f sampleapp/k8s/jaeger-app.yaml
kubectl apply -n observability -f sampleapp/k8s/test-app-1.yaml
kubectl apply -n observability -f sampleapp/k8s/test-app-2.yaml
```

# Data Sources - Jaeger 

Pattern: `<jaeger-instance>.<namespace>.svc.cluster.local:16686`

```yaml
URL: simpletest-query.observability.svc.cluster.local:16686
```