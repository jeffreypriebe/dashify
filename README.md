# dashify [![NPM version](https://img.shields.io/npm/v/dashify.svg?style=flat)](https://www.npmjs.com/package/dashify) [![Build Status](https://img.shields.io/travis/jonschlinkert/dashify.svg?style=flat)](https://travis-ci.org/jonschlinkert/dashify)

> Convert a camelcase or space-separated string to a dash-separated string.

I'm using this for converting object keys to dash-case. Most slugify libs are too heavy for this, so I made this as a fast and light alternative.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install dashify --save
```

## Usage

```js
var dashify = require('dashify');

dashify('fooBar');
//=> 'foo-bar'
dashify('fooBarBaz');
//=> 'foo-bar-baz'
dashify('foo bar');
//=> 'foo-bar'
dashify('foo barBaz');
//=> 'foo-bar-baz'
dashify('foo barBaz quux');
//=> 'foo-bar-baz-quux'
```

## Related projects

Some other awesome string libs:

* [pascalcase](https://www.npmjs.com/package/pascalcase): Convert a string to pascal-case. | [homepage](https://github.com/jonschlinkert/pascalcase)
* [romanize](https://www.npmjs.com/package/romanize): Convert arabic numbers to roman numerals (useful for books, outlines, documentation, slide decks, etc) | [homepage](https://github.com/jonschlinkert/romanize)
* [word-wrap](https://www.npmjs.com/package/word-wrap): Wrap words to a specified length. | [homepage](https://github.com/jonschlinkert/word-wrap)
* [wordcount](https://www.npmjs.com/package/wordcount): Count the words in a string. Support for english, CJK and Cyrillic. | [homepage](https://github.com/jonschlinkert/wordcount)

## Running tests

Install dev dependencies:

```sh
$ npm install -d && npm test
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/dashify/issues/new).

If this project doesn't do what you need, [please let us know](https://github.com/jonschlinkert/dashify/issues)!

## Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright © 2015-2016, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT license](https://github.com/jonschlinkert/dashify/blob/master/LICENSE).

***

_This file was generated by [verb](https://github.com/verbose/verb), v0.9.0, on May 23, 2016._