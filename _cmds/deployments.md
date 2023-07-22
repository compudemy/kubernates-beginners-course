See all Created Deployment

```bash
    kubectl get deployment
```
Replace a deployment

```bash
    kubectl replace -f deployment-defination.yaml 
```

See Rollback Status

```
    kubectl rollback status deployment/<deployment-name>
```

see Revisions History

```
    kubectl rollback history deployment/<deployment-name>
```

Rollback to specific version

```
    kubectl rollout undo deployment/<deployment-name> --to-revision=2
```