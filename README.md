# rc-tree-select
---

React TreeSelect Component


[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![gemnasium deps][gemnasium-image]][gemnasium-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]
[![Sauce Test Status](https://saucelabs.com/buildstatus/rc-tree-select)](https://saucelabs.com/u/rc-tree-select)

[![Sauce Test Status](https://saucelabs.com/browser-matrix/rc-tree-select.svg)](https://saucelabs.com/u/rc-tree-select)

[npm-image]: http://img.shields.io/npm/v/rc-tree-select.svg?style=flat-square
[npm-url]: http://npmjs.org/package/rc-tree-select
[travis-image]: https://img.shields.io/travis/react-component/tree-select.svg?style=flat-square
[travis-url]: https://travis-ci.org/react-component/tree-select
[coveralls-image]: https://img.shields.io/coveralls/react-component/tree-select.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/react-component/tree-select?branch=master
[gemnasium-image]: http://img.shields.io/gemnasium/react-component/tree-select.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/react-component/tree-select
[node-image]: https://img.shields.io/badge/node.js-%3E=_0.10-green.svg?style=flat-square
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/rc-tree-select.svg?style=flat-square
[download-url]: https://npmjs.org/package/rc-tree-select


## Browser Support

|![IE](https://raw.github.com/alrra/browser-logos/master/internet-explorer/internet-explorer_48x48.png) | ![Chrome](https://raw.github.com/alrra/browser-logos/master/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/firefox/firefox_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/opera/opera_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/safari/safari_48x48.png)|
| --- | --- | --- | --- | --- |
| IE 8+ ✔ | Chrome 31.0+ ✔ | Firefox 31.0+ ✔ | Opera 30.0+ ✔ | Safari 7.0+ ✔ |

## Screenshots

<img src="" width="288"/>


## Development

```
npm install
npm start
```

## Example

http://localhost:8000/examples/


online example: http://react-component.github.io/tree-select/


## Feature

* support ie8,ie8+,chrome,firefox,safari

### Keyboard


## install


[![rc-tree-select](https://nodei.co/npm/rc-tree-select.png)](https://npmjs.org/package/rc-tree-select)


## Usage

see examples

## API

### TreeSelect props

| name     | description    | type     | default      |
|----------|----------------|----------|--------------|
|className | additional css class of root dom node | String | '' |
|prefixCls | prefix class | String | '' |
|multiple | whether multiple select | bool | false |
|[select-props](https://github.com/react-component/select#select-props) | the same as select props | ||
|treeProps | the same as tree props  (except onSelect and onCheck) | | [tree-props](https://github.com/react-component/tree#tree-props) |

### TreeNode props

| name     | description    | type     | default      |
|----------|----------------|----------|--------------|
|value | default as optionFilterProp | String | 'value' |
|[treenode-props](https://github.com/react-component/tree#treenode-props) | the same as treeNode props|||


## Test Case

http://localhost:8000/tests/runner.html?coverage

## Coverage

http://localhost:8000/node_modules/rc-server/node_modules/node-jscover/lib/front-end/jscoverage.html?w=http://localhost:8000/tests/runner.html?coverage

## License
rc-tree-select is released under the MIT license.