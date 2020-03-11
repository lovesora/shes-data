## Run pod with custom image on k8s

```bash
kubectl run -n default --generator=run-pod/v1 -i --tty --rm pod-debug --image=${id}.dkr.ecr.ap-northeast-1.amazonaws.com/${path} --command sh
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTIyNjMzOTQ0NF19
-->