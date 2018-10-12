# @soorajcode/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@soorajcode/tiny.svg)](https://www.npmjs.com/package/@soorajcode/tiny)

[![Twitter](https://img.shields.io/twitter/url/https/github.com/soorajvinodan/tinymodule.svg?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fsoorajvinodan%2Ftinymodule)

(https://www.npmjs.com/package/@soorajcode/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @soorajcode/tiny
```

## Usage

```js
const tiny = require("@soorajcode/tiny");

tiny("So much space hehe!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
