# kubernetes-commands-cheatsheet

```bash
kubectl get pods
```

```bash
kubectl get pods -l app=<label-selector>
```

```bash
kubectl get pods -o yaml
```

```bash
kubectl get pods -o wide
```

```bash
kubectl get services
```

```bash
kubectl get deployments
```

```bash
kubectl get nodes
```

```bash
kubectl describe pods
```

```bash
kubectl logs [pod_name]
```

```bash
kubectl cluster-info
```

```bash
kubectl get configMaps
```

```bash
kubectl proxy
```

```bash
kubectl describe pod [pod_name]
```

```bash
kubectl describe services/[service_name]
```

```bash
kubectl expose deployment/[deployment_name] --type="NodePort" --port=8080
```

```bash
kubectl delete service -l <label>
```

```bash
kubectl label pod [pod_name] <label>
```

```bash
kubectl rollout status deployments/[deployment_name]
```

```bash
kubectl rollout undo deployments/[deployment_name]
```

```bash
kubectl scale deployments/[deployment_name] --replicas=[number_of_replicas]
```

```bash
kubectl run [deployment_name] --image=[image_and_tag] --port=8080
```

```bash
kubectl config view
```


```bash
kubectl config get-contexts
```


```bash
kubectl get configmaps
```


```bash
kubectl get secrets
```


```bash
kubectl get configmap [config-map-name] -o yaml
```


```bash
kubectl get secret [secrets-name] -o yaml
```
