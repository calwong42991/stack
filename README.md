# stack

[![build:?](https://travis-ci.org/eyas-ranjous/datatructures-js/stack.svg?branch=master)](https://travis-ci.org/eyas-ranjous/datatructures-js/stack) 
[![npm](https://img.shields.io/npm/v/@datastructures-js/stack.svg)](https://www.npmjs.com/package/@datastructures-js/stack)
[![npm](https://img.shields.io/npm/dm/@datastructures-js/stack.svg)](https://www.npmjs.com/packages/@datastructures-js/stack) [![npm](https://img.shields.io/badge/node-%3E=%206.0-blue.svg)](https://www.npmjs.com/package/@datastructures-js/stack)

elements data type: any type.

## Usage
```js
const stackFn = require('@datastructures-js/stack');
const stack = stackFn();
```

## API

**.push(element)** 

push an element to the top of the stack.
```javascript
stack.push('test');
```

**.peek()** 

returns the top element in the stack.
```javascript
console.log(stack.peek()); // test
```

**.pop()** 

pops the top element of the stack.
```javascript
console.log(stack.pop()); // test
console.log(stack.peek()); // null
```

**.isEmpty()** 

checks if the stack is empty.
```javascript
console.log(stack.isEmpty()); // true
```

**.length()** 

returns the length length of the stack.
```javascript
console.log(stack.length()); // 0
```

## Build
```
grunt build
```

## License
The MIT License. Full License is [here](https://github.com/eyas-ranjous/datastructures-js/stack/blob/master/LICENSE)
