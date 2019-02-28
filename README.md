
# @askreddy17/tiny

Removes all spaces from a string.

## Install

```
$ npm install @askreddy17/tiny
```

## Usage

```js
const tiny = require("@askreddy17/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
