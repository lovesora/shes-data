## regex group capture

```bash
rg -o "\.version\s*=\s*[\"']([0-9a-zA-Z._-]+)['\"]" -r '$1' < $pod_spec_file
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbODI4NjEzNTkwXX0=
-->