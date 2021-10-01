# Bongo isOdd
```js
function isOdd(n) {
    let result;

    do {
        result = Math.round(Math.random())
    } while (result === n % 2);

    return Boolean(result);
}
```