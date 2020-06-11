# @peterpanhihi/tiny

![Image of version](https://img.shields.io/badge/npm-v1.0.0-blue)

Removes all spaces from a string.

## Install

```
$ npm install @peterpanhihi/tiny
```

## Usage

```js
const tiny = require("@peterpanhihi/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```