# baseline.css

[![Version Badge][version-image]][project-url]
[![Build Status][build-image]][build-url]
[![Dependencies][dependencies-image]][project-url]
[![License][license-image]][license-url]
[![File Size][file-size-image]][project-url]

> Opinionated baseline stylesheet.

Baseline is a modern CSS reset, combining the fantastic [normalize.css](https://github.com/necolas/normalize.css) with a set of opinionated base styles to provide a consistent foundation in which to build on top of. Baseline does not assume the theme of your application and therefore provides very little in the way of aesthetics (colors, borders, margins, paddings, etc.). Many of the opinionated styles, such as typography, can be configured via CSS variables that are compiled by PostCSS.

## Features

* Automatically includes [normalize.css](https://github.com/necolas/normalize.css)
* Optimized for responsive design by resetting the box model to `border-box`
* Ensures the page always fills at least the entire height of the viewport
* Removes the margin, padding, and border for all elements
* Remove `-webkit-tap-highlight-color` from all applicable elements
* Basic starting point for typography including font family, font size, font color, line height, and headings
* All images are responsive by default
* Wide variety of form optimizations based on best practices
* Remove click delay on clickable elements on mobile devices
* Accessibility helpers
* Styles optimized for printing
* Plus many more!

## Installation

Download the [development](http://github.com/ryanmorr/baseline.css/raw/master/dist/baseline.css) or [minified](http://github.com/ryanmorr/baseline.css/raw/master/dist/baseline.min.css) version, or install it in one of the following ways:

``` sh
npm install ryanmorr/baseline.css

bower install ryanmorr/baseline.css
```

## License

This project is dedicated to the public domain as described by the [Unlicense](http://unlicense.org/).

[project-url]: https://github.com/ryanmorr/baseline.css
[version-image]: https://badge.fury.io/gh/ryanmorr%2Fbaseline.css.svg
[build-url]: https://travis-ci.org/ryanmorr/baseline.css
[build-image]: https://travis-ci.org/ryanmorr/baseline.css.svg
[dependencies-image]: https://david-dm.org/ryanmorr/baseline.css.svg
[license-image]: https://img.shields.io/badge/license-Unlicense-blue.svg
[license-url]: UNLICENSE
[file-size-image]: https://badge-size.herokuapp.com/ryanmorr/baseline.css/master/dist/baseline.min.css.svg?color=blue&label=file%20size