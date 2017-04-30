Inline SVG extension for the HTML Webpack Plugin
========================================
[![npm version](https://badge.fury.io/js/html-webpack-inline-svg-plugin.svg)](https://badge.fury.io/js/html-webpack-inline-svg-plugin) [![Build status](https://travis-ci.org/thegc/html-webpack-inline-svg-plugin.svg?branch=master)](https://travis-ci.org/thegc/html-webpack-inline-svg-plugin) [![js-semistandard-style](https://img.shields.io/badge/code%20style-semistandard-brightgreen.svg?style=flat-square)](https://github.com/Flet/semistandard)

Allows you to inline SVGs that are parsed by [html-webpack-plugin](https://github.com/ampedandwired/html-webpack-plugin).

Now you can serve SVGs easily to all devices, with or without javascript. Combined with techniques such as: [SVG as Icon Font](https://css-tricks.com/svg-sprites-use-better-icon-fonts/) you have a simple way of ensuring your icons are visible.

Installation
------------
Install the plugin with npm:
```shell
$ npm install --save-dev html-webpack-inline-svg-plugin
```

**or** [yarn](https://yarnpkg.com/):
```shell
$ yarn add html-webpack-inline-svg-plugin --dev
```

Usage
-----------
Require the plugin in your webpack config:

```javascript
const HtmlWebpackInlineSVGPlugin = require('html-webpack-inline-svg-plugin');
```

Add the plugin to your webpack config as follows:

```javascript
plugins: [
    new HtmlWebpackPlugin(),
    new HtmlWebpackInlineSVGPlugin()
]
```