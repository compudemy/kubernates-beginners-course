Create a Pod in dev namespace

```bash
    kubectl run nginx-dev --image=nginx
```

Get Pod in a namespace

```bash
    kubectl get pods -n <namespace>
```

Example

```bash
    kubectl get pods -n dev
```

Delete a namespace

```bash
    kubectl delete <namespace> <namespace-name></namespace-name>
```

Example 

```bash
kubectl delete namespace dev
```