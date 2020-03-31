## Disk performance on ubuntu

```bash
dd if=/dev/zero of=/tmp/output conv=fdatasync bs=384k count=1k; rm -f /tmp/output
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwODI2NDEzMDldfQ==
-->