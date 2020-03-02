## Insert file content below the matched line
```bash
sed '/cdef/r add.txt' input.txt
cat input.txt | sed '/cdef/r add.txt'
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyNjkxMjI5MTYsLTE4Mzk2MzY4MzNdfQ
==
-->