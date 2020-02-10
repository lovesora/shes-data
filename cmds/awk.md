## Remove first line and excute commands with special column
```bash
helm list | awk 'NR > 1 {cmd="helm get values $1 > $1.yaml"; system(cmd)}'
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMjA0ODM5MzFdfQ==
-->