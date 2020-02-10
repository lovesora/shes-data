## Insert file content below regexp match line
```bash
sed '/cdef/r add.txt' input.txt
cat input.txt | sed '/cdef/r add.txt'
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4Mzk2MzY4MzNdfQ==
-->