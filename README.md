# Simple but Useful CSS Classes

[![DevOps By Rultor.com](https://www.rultor.com/b/yegor256/drops)](https://www.rultor.com/p/yegor256/drops)

[![grunt](https://github.com/yegor256/drops/actions/workflows/grunt.yml/badge.svg)](https://github.com/yegor256/drops/actions/workflows/grunt.yml)
[![PDD status](https://www.0pdd.com/svg?name=yegor256/drops)](https://www.0pdd.com/p?name=teamed/yegor256/drops)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/yegor256/drops/blob/master/LICENSE.txt)
[![NPM version](https://badge.fury.io/js/drops.svg)](https://badge.fury.io/js/drops)
[![Hits-of-Code](https://hitsofcode.com/github/yegor256/drops)](https://hitsofcode.com/view/github/yegor256/drops)

First, you add it to your HTML:

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/drops@0.2.0/dist/drops-0.2.0.min.css"/>
  </head>
</html>
```

And then, instead of this:

```html
<p style="color: tomato; font-weight: bold; text-align: right;">Hello</p>
```

You do this:

```html
<p class="tomato bold right">Hello</p>
```

Here is a full list of "drops" (excluding the colors):

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
| `smaller` | `font-size: .8em;` |
| `larger` | `font-size: 1.2em;` |
| `invisible` | `display: none;` |
| `block` | `display: block;` |
| `inline` | `display: inline;` |
| `inline-block` | `display: inline-block;` |
| `position-static` | `position: static;` |
| `position-relative` | `position: relative;` |
| `position-absolute` | `position: absolute;` |
| `position-fixed` | `position: fixed;` |
| `position-sticky` | `position: sticky;` |

There is also a set of drops for responsive design, like `desktop-only` and
`no-printer` for `desktop`, `printer`, `mobile`, and `tablet`.

Also, all [140 web colors](https://en.wikipedia.org/wiki/Web_colors)
are supported, like `tomato` or `blueviolet`.

## How to contribute

Fork repository, make changes, send us a pull request. We will review
your changes and apply them to the `master` branch shortly, provided
they don't violate our quality standards. To avoid frustration, before
sending us your pull request please run full Grunt build:

```bash
npm install
npm test
```
