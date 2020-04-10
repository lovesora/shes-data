## List all listened port

```bash
netstat -nulp
```

## Check if port has been used

```bash
lsof -i :${port:-80}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTgxMTAwOTYwNl19
-->