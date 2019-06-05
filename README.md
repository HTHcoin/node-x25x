node-x22i
===============
Cryptocurrency hashing functions for SIN

Current version v1.0.0
Usage
-------
```js
var x25x = require('node-x25x');
var buf = Buffer.from('password', 'utf8');
var hash = x25x.x25x(buf);
console.log(hash);
// => <Buffer cb 78 00 4e 36 14 56 0b c1 98 cd e0 5b 17 a5 06 13 7c ac 77 5a cf e0 fc 4e e2 cf 23 30 54 2a 17>
