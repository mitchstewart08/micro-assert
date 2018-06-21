# micro-assert
A micro library for fast and easy testing of primitives, objects, and arrays

#How-to
Import into your js file and instantiate a new assert obj
```
import Assert from './assert.js';
const test = new Assert();
```

assert is the only method you need to use, the library will worry about data types and coericon for you
```
test.assert(expectation, result, "Test name here");
```
Works great with [Quokka](https://quokkajs.com/docs/index.html)
![Example of micro-assert with Quokka](https://i.imgur.com/rxFaWXQ.png)