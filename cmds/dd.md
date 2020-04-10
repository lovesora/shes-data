## Disk performance

```bash
dd if=/dev/zero of=/tmp/output conv=fdatasync bs=384k count=1k; rm -f /tmp/output
dd if=/dev/zero of=/tmp/output conv=fdatasync bs=4k count=100k; rm -f /tmp/output
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjQ1NjIxMTEyLC0yMDgyNjQxMzA5XX0=
-->