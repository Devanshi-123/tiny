# @devanshi_goel/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@devanshi_goel/tiny)
[![npm bundle size](https://img.shields.io/bundlephobia/min/tiny?color=red)

Removes all spaces from a string.

## Install

```
$ npm install @devanshi_goel/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
