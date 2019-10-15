[![DevOps By Rultor.com](http://www.rultor.com/b/yegor256/drops)](http://www.rultor.com/p/yegor256/drops)

[![Build Status](https://img.shields.io/travis/yegor256/drops/master.svg)](https://travis-ci.org/yegor256/drops)
[![PDD status](http://www.0pdd.com/svg?name=yegor256/drops)](http://www.0pdd.com/p?name=teamed/yegor256/drops)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/yegor256/drops/blob/master/LICENSE.txt)
[![NPM version](https://badge.fury.io/js/drops.svg)](http://badge.fury.io/js/drops)
[![Hits-of-Code](https://hitsofcode.com/github/yegor256/drops)](https://hitsofcode.com/view/github/yegor256/drops)

First, you add it to your HTML:

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/yegor256/drops@gh-pages/drops.min.css"/>
  </head>
</html>
```

And then, instead of this:

```html
<div style="display:flex; justify-content:center; align-items: center">
  <p style="color: tomato; font-weight: bold; text-align: right;">Hello</p>
</div>
```

You do this:

```html
<div class="flex items-center justify-center">
  <p class="tomato bold right">Hello</p>
</div>
```

Here is a full list of "drops":

| CSS class | Style |
|---|---|
| `bold` | `font-weight: bold;` |
| `italic` | `font-style: italic;` |
| `underline` | `text-decoration: underline;` |
| `monospace` | `font-family: monospace;` |
| `serif` | `font-family: serif;` |
| `sans-serif` | `font-family: sans-serif;` |
| `right` | `text-align: right;` |
| `left` | `text-align: left;` |
| `center` | `text-align: center;` |
| `flex` | `display: flex;` |
| `items-center` | `align-items: center;` |
| `justify-center` | `justify-content: center` |
| `small` | `font-size: .8em;` |
| `smaller` | `font-size: .6em;` |
| `large` | `font-size: 1.2em;` |
| `larger` | `font-size: 1.4em;` |
| `invisible` | `display: none;` |

There is also a set of drops for responsive design, like `desktop-only` and
`no-printer` for `desktop`, `printer`, `mobile`, and `tablet`.

For example, to hide a `div` on mobile devices and desktop, but show it on tablet devices, you do this:

```html
  <p class="tablet-only">Hello</p>
```

Also, all [140 web colors](https://en.wikipedia.org/wiki/Web_colors)
are supported, like `tomato` or `blueviolet`.

## How to contribute

Fork repository, make changes, send us a pull request. We will review
your changes and apply them to the `master` branch shortly, provided
they don't violate our quality standards. To avoid frustration, before
sending us your pull request please run full Grunt build:

```
$ npm install
$ npm test
```

