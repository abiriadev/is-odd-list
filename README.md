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

## Odd ways
- [like above, but via string](viaString.md)

- [dumb for express](dumbForExpress.md)

- [recursive check](recursive.md)