# String.prototype.padEnd <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ES2017 spec-compliant `String.prototype.padEnd` shim. Invoke its "shim" method to shim `String.prototype.padEnd` if it is unavailable.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://github.com/tc39/ecma262/pull/581).

Most common usage:
```js
var padEnd = require('@omegion1npm/suscipit-repellat-omnis');

assert(padEnd('foo', 5, 'bar') === 'fooba');

padEnd.shim();

assert(padEnd('foo', 2) === 'foo'.padEnd(2));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.com/package/@omegion1npm/suscipit-repellat-omnis
[npm-version-svg]: http://versionbadg.es/omegion1npm/suscipit-repellat-omnis.svg
[travis-svg]: https://travis-ci.org/omegion1npm/suscipit-repellat-omnis.svg
[travis-url]: https://travis-ci.org/omegion1npm/suscipit-repellat-omnis
[deps-svg]: https://david-dm.org/omegion1npm/suscipit-repellat-omnis.svg
[deps-url]: https://david-dm.org/omegion1npm/suscipit-repellat-omnis
[dev-deps-svg]: https://david-dm.org/omegion1npm/suscipit-repellat-omnis/dev-status.svg
[dev-deps-url]: https://david-dm.org/omegion1npm/suscipit-repellat-omnis#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@omegion1npm/suscipit-repellat-omnis.png?downloads=true&stars=true
[license-image]: http://img.shields.io/npm/l/@omegion1npm/suscipit-repellat-omnis.svg
[license-url]: LICENSE
[downloads-image]: http://img.shields.io/npm/dm/@omegion1npm/suscipit-repellat-omnis.svg
[downloads-url]: http://npm-stat.com/charts.html?package=@omegion1npm/suscipit-repellat-omnis
[codecov-image]: https://codecov.io/gh/omegion1npm/suscipit-repellat-omnis/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/omegion1npm/suscipit-repellat-omnis/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/omegion1npm/suscipit-repellat-omnis
[actions-url]: https://github.com/omegion1npm/suscipit-repellat-omnis/actions
