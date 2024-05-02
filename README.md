# @womorg/totam-commodi-ratione <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@womorg/totam-commodi-ratione');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@womorg/totam-commodi-ratione
[npm-version-svg]: https://versionbadg.es/inspect-js/@womorg/totam-commodi-ratione.svg
[deps-svg]: https://david-dm.org/inspect-js/@womorg/totam-commodi-ratione.svg
[deps-url]: https://david-dm.org/inspect-js/@womorg/totam-commodi-ratione
[dev-deps-svg]: https://david-dm.org/inspect-js/@womorg/totam-commodi-ratione/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@womorg/totam-commodi-ratione#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@womorg/totam-commodi-ratione.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@womorg/totam-commodi-ratione.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@womorg/totam-commodi-ratione.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@womorg/totam-commodi-ratione
[codecov-image]: https://codecov.io/gh/inspect-js/@womorg/totam-commodi-ratione/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@womorg/totam-commodi-ratione/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@womorg/totam-commodi-ratione
[actions-url]: https://github.com/womorg/totam-commodi-ratione/actions
