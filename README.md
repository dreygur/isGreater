# isGreater

## Usage

```js
const isGreater = require('isgreater');
```

### isGreater(value, comparator)

Validates if a value is greater than a comparator value.

```js
var a = 10,
    b = 0;

var bool = isGreater(a, b);
// returns true
```

__Note__: this method validates that both values are numeric before making the comparison. For non-numeric values, the method returns `false`.

### Examples

```js
console.log(isGreater(2, 1 );
// returns true
 
console.log(isGreater(0, 1));
// returns false
```
