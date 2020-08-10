# cluster-config-management
config-management-operator.yaml is provided by Google Anthos, an open source project under Apache 2 license

Configuration as code for Kubernetes Cluster

```console
kubectl apply -f config-management-operator.yaml
kubectl get pods -n kube-system

kubectl apply -f config-management.yaml
kubectl get pods -n config-management-system

#Wait several sec and check
kubectl get pods -n samples
```


