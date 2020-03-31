## Docker rm all contianers

```bash
docker kill $(docker ps -q)
docker rm $(docker ps -a -q)
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4MjI1MDczMV19
-->