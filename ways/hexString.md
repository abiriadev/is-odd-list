## hexString
```js
function isOdd(n) {
    return ['1', '3', '5', '7', '9', 'b', 'd', 'f'].includes((+n).toString(16).slice(-1));
}
```
