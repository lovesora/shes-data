## [FP] (first-class function) Do not define function which only arround another

```js
// ignorant
const getServerStuff = callback => ajaxCall(json => callback(json));

// enlightened
const getServerStuff = ajaxCall;
```

## [FP] (first-class function) Define more general and reusable function

- Do not tie ourselves to specific data

```js
// specific to our current blog
const validArticles = articles =>
  articles.filter(article => article !== null && article !== undefined),

// vastly more relevant for future projects
const compact = xs => xs.filter(x => x !== null && x !== undefined);
```

## [FP] (first-class function) Care about `this`

```js
const fs = require(['fs']);

// scary
fs.readFile('freaky_friday.txt', Db.save);

// less so
fs.readFile('freaky_friday.txt', Db.save.bind(Db));
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY0ODc3MzAxMiwtMTgxMTUxNDc1OSwxMz
M3ODE4ODg4XX0=
-->