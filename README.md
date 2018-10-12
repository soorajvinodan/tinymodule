# @soorajcode/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@soorajcode/tiny.svg)](https://www.npmjs.com/package/@bamblehorse/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@soorajcode/tiny.svg)](https://www.npmjs.com/package/@bamblehorse/tiny)

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
