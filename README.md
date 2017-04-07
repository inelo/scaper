Scaper
=========

A small library providing utility methods to `escape` and `unescape` HTML entities

## Installation

  npm install scaper --save

## Usage
```
  var scaper = require('scaper')
      escape = scaper.escape,
      unescape = scaper.unescape;

  var html = '<h1>Hello World</h1>',
      escaped = escape(html),
      unescaped = unescape(escaped);

  console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);
```
## Tests

  npm test

## Release History

* 0.1.0 Initial release
