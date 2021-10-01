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
  return Boolean(n & 1);
}
```

## Odd ways
- [like above, but via string](ways/viaString.md)

- [dumb for express](ways/dumbForExpress.md)

- [recursive check](ways/recursive.md)