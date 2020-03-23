## Git shallow clone

```bash
mkdir ${repo_name:-repo}
cd $repo_name
git init
git remote add origin $origin
git fetch --depth 1 origin $commit_id
git checkout $commit_id
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ1NTAxMTA4N119
-->