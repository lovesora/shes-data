## [FP] (first-class function) Do not define function which only arround another

```js
// ignorant
const getServerStuff = callback => ajaxCall(json => callback(json));

// enlightened
const getServerStuff = ajaxCall;
```

## [FP] (first-class function) Define more general and reusable function

```js
// specific to our current blog
const validArticles = articles =>
  articles.filter(article => article !== null && article !== undefined),

// vastly more relevant for future projects
const compact = xs => xs.filter(x => x !== null && x !== undefined);
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4MTE1MTQ3NTksMTMzNzgxODg4OF19
-->