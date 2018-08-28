# @mynormh/tiny
[![npm (scoped)](https://img.shields.io/npm/v/@mynormh/tiny.svg)](https://github.com/mynormh/tiny) [![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@mynormh/tiny.svg)](https://github.com/mynormh/tiny)

Removes all spaces from a string.

## Install
`$ npm install @bamblehorse/tiny`

## Usage
```
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
