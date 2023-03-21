
```
kubectl apply -f scopek8s.yaml
kubectl label namespace default scope=enabled
kubectl apply -f <other_yaml>
```