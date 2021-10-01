## Ternary Digit Sum

By https://github.com/EatChangmyeong

```js
function isOdd(n) {
	n = Math.abs(n);
	while(n >= 3)
		n = [...n.toString(3)].map(Number).reduce((a, b) => a + b);
	return n == 1;
}
```
