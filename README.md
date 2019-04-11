# baseline.css

[![Version Badge][version-image]][project-url]
[![Build Status][build-image]][build-url]
[![License][license-image]][license-url]

> A modern and opinionated baseline stylesheet.

## Install

Download the [development](http://github.com/ryanmorr/baseline.css/raw/master/baseline.css) or [minified](http://github.com/ryanmorr/baseline.css/raw/master/baseline.min.css) version, or install via NPM:

``` sh
npm install @ryanmorr/baseline.css
```

## Features

Compiling elements of [normalize.css](https://github.com/necolas/normalize.css), [sanitize.css](https://github.com/csstools/sanitize.css), [Bootstrap](https://github.com/twbs/bootstrap), [ress](https://github.com/filipelinhares/ress), [CSS Remedy](https://github.com/mozdevs/cssremedy), and others with my own personal preferences while only supporting the latest browsers. Some of the features include:

* Most of the normalizations from normalize.css.
* Resets the box model to `border-box`.
* Removes the margin and padding of all elements.
* Sets the background of all elements to transparent and prevents background repeating.
* Render text with grayscale antialiasing on high DPI screens.
* Headings and typography are optimized for `rem` units.
* Images and other media elements are responsive by default.
* Removes the default styling for buttons and select elements.
* Removes click delay on clickable elements on mobile devices.
* Future-proof rule to remove focus outlines for mouse/pointer based interactions.
* Accessibility helpers.
* Styles optimized for printing.

## License

This project is dedicated to the public domain as described by the [Unlicense](http://unlicense.org/).

[project-url]: https://github.com/ryanmorr/baseline.css
[version-image]: https://badge.fury.io/gh/ryanmorr%2Fbaseline.css.svg
[build-url]: https://travis-ci.org/ryanmorr/baseline.css
[build-image]: https://travis-ci.org/ryanmorr/baseline.css.svg
[license-image]: https://img.shields.io/badge/license-Unlicense-blue.svg
[license-url]: UNLICENSE