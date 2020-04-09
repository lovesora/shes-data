## Post json data with multiple lines
**Quote** your variables `"${body}"`, before invoking `echo` shell splits that string into multiple arguments using the `Internal Field Separator` (IFS), and passes that resulting list of arguments to `echo`. By default, the `IFS` is set to whitespace (spaces, tabs, and newlines).

```bash
data='{"body": "'"$(echo "${body}" | awk '{printf "%s<br>", $0}')"'"}'
curl -s --data "${data}" -X PATCH $api
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDgxMDU3OTA5XX0=
-->