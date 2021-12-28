# zybwin/tiny
[![npm (scoped)](https://img.shields.io/badge/npm-v1.0.0-green)](https://github.com/ZhouDaniel/tiny.git)

Removes all spaces from a string

## install
```js
npm install @zybwin/tiny
```

Usage
```js
const tiny = require('@zybwin/tiny');
tiny('so much space') 
// => 'somuchspace'
tiny(133)
// => Uncaught TypeError Tiny wants a string!
```
