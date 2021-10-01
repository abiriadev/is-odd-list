## dumb for express
```js
function isOdd(n) {
    if (n < 0) n = Math.abs(n);
    let result = false;
    for (let i = 0; i < n; i++) result = !result;
    return result;
}
```