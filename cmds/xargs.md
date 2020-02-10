## `xargs` with `-I` option
```bash
ls | xargs -n1 -I file sh -c 'mv file file.bak'
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDI3MzEyNjc4XX0=
-->