# microtime-x - Get current time in microseconds (cross-environment solution)

Returns the number of microseconds elapsed since 1 January 1970 00:00:00 UTC

In browser relies on `performance.now` or it's engine specific variant if available, in Node.js [microtime-nodejs](https://www.npmjs.com/package/microtime-nodejs) by yuri0 is used (if supported). If none of the mentioned works then `Date.now()` result multiplied by 1000 is returned

## Installation
### NPM

In your project path:

	$ npm install @limeandcoconut/microtime-x

### Browser

You can easily bundle npm packages for browser with [modules-webmake](https://github.com/medikoo/modules-webmake)

## Tests [![Build Status](https://travis-ci.org/limeandcoconut/microtime-x.png)](https://travis-ci.org/limeandcoconut/microtime-x)

	$ npm test
