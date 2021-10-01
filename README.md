# awesome-is-odd
A list of odd ways for is-odd functions with Javascript.

## The most common way
```js
function isOdd(n) {
  return n % 2 === 1;
}
```

a bit weird way:
```js
function isOdd(n) {
  return n & 1
}
```

dumb for express
```js
function isOdd(n) {
    if (n < 0) n = Math.abs(n);
    
    let result = false;
    for (let i = 0; i < n; i++) {
        if (result === false) result = true;
        else result = false;
    }
    
    return result;
}
```
