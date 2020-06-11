## List all deleted file in git history

```bash
git log --diff-filter=D --summary | grep delete
```

## Show file log (include deleted file)

```bash
git log --all -- ${FILEPATH}
```

## Show files change between two commits

```bash
git diff --stat ${GIT_REVISION} $(git merge-base ${GIT_REVISION} ${PULL_BASE_SHA}) -- path/to/files
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTIxOTM5OTU0OSwtNDU3MjE1MzkyXX0=
-->