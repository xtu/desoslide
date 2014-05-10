# desoSlide [![Build Status](https://travis-ci.org/sylouuu/desoslide.svg)](https://travis-ci.org/sylouuu/desoslide) [![GitHub version](https://d25lcipzij17d.cloudfront.net/badge.svg?id=gh&type=5&v=2.0.0-rc1)](http://badge.fury.io/gh/sylouuu%2Fdesoslide) [![devDependency Status](https://david-dm.org/sylouuu/desoslide/dev-status.svg?theme=shields.io)](https://david-dm.org/sylouuu/desoslide#info=devDependencies)

## Overview, demo, documentation, release notes and tests

**http://sylouuu.github.io/desoslide**

## Dependencies

* [jQuery](jquery.com/download/)
* [animate.css](https://github.com/daneden/animate.css) for using `effect.provider: 'animate'` (default)
* [magic](https://github.com/miniMAC/magic) for using `effect.provider: 'magic'`

## Build `dist/`

Compile dist files:

* `dist/less/jquery.desoslide.less` to
    * `dist/css/jquery.desoslide.css`
    * `dist/css/jquery.desoslide.min.css`

* `dist/js/jquery.desoslide.js` to
    * `dist/js/jquery.desoslide.min.js`

```
npm install
gulp build
```

## Run tests

```
npm install
gulp tests
```

## Contributing

See <a href="CONTRIBUTING.md">contributing</a> file.

## Changelog

See <a href="https://github.com/sylouuu/desoslide/releases">releases</a> page or <a href="http://sylouuu.github.io/desoslide/doc/release-notes.html">release notes</a> (UI).

## License

See <a href="LICENSE.md">license</a> file.
