### Symbols
Starting with ECMAScript 2015, symbol is a primitive data type, just like number and string.
symbol values are created by calling the Symbol constructor.

```
let sym1 = Symbol();

let sym2 = Symbol("key"); // optional string key
```
Symbols are immutable, and unique.

```
let sym2 = Symbol("key");
let sym3 = Symbol("key");

sym2 === sym3; // false, symbols are unique
```
