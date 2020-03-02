## Checking Rollout History of a Deployment

```bash
kubectl rollout history deployment ${DEPLOYMENT:-nginx-deployment}
```

## Rolling Back to a Previous Revision

```bash
kubectl rollout undo deployment ${DEPLOYMENT:-nginx-deployment}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTgxMTQwOTc4OF19
-->