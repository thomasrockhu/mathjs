---
layout: default
---

# Function floor

Round a value towards minus infinity.
For matrices, the function is evaluated element wise.


## Syntax

```js
math.floor(x)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | Number &#124; BigNumber &#124; Boolean &#124; Complex &#124; Array &#124; Matrix | Number to be rounded

### Returns

Type | Description
---- | -----------
Number &#124; BigNumber &#124; Complex &#124; Array &#124; Matrix | Rounded value


## Examples

```js
math.floor(3.2);              // returns Number 3
math.floor(3.8);              // returns Number 3
math.floor(-4.2);             // returns Number -5
math.floor(-4.7);             // returns Number -5

var c = math.complex(3.2, -2.7);
math.floor(c);                // returns Complex 3 - 3i

math.floor([3.2, 3.8, -4.7]); // returns Array [3, 3, -5]
```


## See also

[ceil](ceil.html),
[fix](fix.html),
[round](round.html)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->