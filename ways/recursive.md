## recursive check:
```js
function isOdd(n) {
  return !n ? false : n < 0 ? true : isOdd(n - 2)
}
```