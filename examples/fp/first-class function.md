## [FP] (first-class function) Do not define function which only arround another

```js
// ignorant
const getServerStuff = callback => ajaxCall(json => callback(json));

// enlightened
const getServerStuff = ajaxCall;
```

## [FP] (first-class function)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ0NzIwMTQ0OCwxMzM3ODE4ODg4XX0=
-->