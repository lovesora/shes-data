## Function.prototype.call

```js
Function.prototype.myCall = function(context, ...args) {
    if (typeof this !== 'function') {
        throw new Error('not fn')
    }
    context = context || window
    context['$fn'] = this
    const result = context['$fn'](...args)
    delete context['$fn']
    return result
}

var add = function() {return this.a + this.b}
var result = add.myCall({a: 1, b: 2})
console.log(result)
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbODc4ODY0NTk1LC0xMjQ1NDkxMDE5XX0=
-->