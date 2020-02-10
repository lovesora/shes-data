## `xargs` with `-I` flag
```bash
ls | xargs -n1 -I file sh -c 'mv file file.bak'
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTIxNjU1NjUwOV19
-->