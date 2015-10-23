# better-hostname [![Build Status](https://travis-ci.org/mvila/better-hostname.svg?branch=master)](https://travis-ci.org/mvila/better-hostname)

Export the machine hostname or `'browser'` when used with [Browserify](http://browserify.org/).

## Installation

```
npm install --save better-hostname
```

## Usage

```javascript
var hostname = require('better-hostname');

console.log(hostname);
```

In case you use [Browserify](http://browserify.org/), this module exports the `'browser'` string.

## License

MIT
