## [rg string] regex group capture

```bash
rg -o "\.version\s*=\s*[\"']([0-9a-zA-Z._-]+)['\"]" -r '$1' < $pod_spec_file
```

## [rg file] search files by blob

```bash
rg --files --max-depth 1 -g '*.podspec'
rg --files --max-depth 1 -E '.*\.podspec'
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY4MTQ1NTkwLC0yNTM5NTY0MDksODI4Nj
EzNTkwXX0=
-->