# Needs more jQuery
Install jquery.
```js
const $ = require("jquery");

function isOdd(n) {
    let result;
    $.each([n], (_, item) => {
        result = n % 2 === 1
    }));
    return result;
}
```