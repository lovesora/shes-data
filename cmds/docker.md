## Docker kill all contianers

```bash
docker kill $(docker ps -q)
docker rm $(docker ps -a -q)
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQ3MDY3OTc5MF19
-->