# strl: String Length
Get the real length of a string

## Installation

```bash
npm install strl
```

## Usage

```js
const length = require('strl')

console.log(length('\u001B[4mtest\u001B[0m'))
// Output: 4

console.log(length('😀'))
// Output: 1

console.log(length('\u001B[4m😀\u001B[0m'))
// Output: 1
```
