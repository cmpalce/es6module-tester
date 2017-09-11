## Description

A simple setup that I use for experimenting and testing different JS ECMAScript 2015 stuff with ES6 modules.
This is also in reference to my blog about "<a href="https://cmpalce.com/blog/how-to-run-es6-module-in-nodejs">https://cmpalce.com/blog/how-to-run-es6-module-in-nodejs</a>".

## Requirements

- NodeJS with version greater than or equal to v6.
- NPM

## Installation
- git clone git@github.com:cmpalce/es6module-tester.git
- cd es6module-tester
- npm install

## How To Use

1. You may use the NPM script: "npm run babel-node [YOUR JS SCRIPT HERE]".
2. Or you may run the full command: "./node_modules/.bin/babel-node --presets es2015 [YOUR JS SCRIPT HERE]".
3. A file "importer.js" is included for a quick test: "./node_modules/.bin/babel-node --presets es2015 impoter.js". If it logs "this is a test function", it means it worked!
