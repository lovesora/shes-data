## List all deleted file in git history

```bash
git log --diff-filter=D --summary | grep delete
```

## Show file log (include deleted file)

```bash
git log --all -- ${FILEPATH}
```

## 
<!--stackedit_data:
eyJoaXN0b3J5IjpbOTgzMzQwODg4LC00NTcyMTUzOTJdfQ==
-->