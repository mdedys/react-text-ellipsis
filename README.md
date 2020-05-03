[![NPM version][npm-image]][npm-url]
[![Build status][ci-image]][ci-url]
[![dependencies Status](https://david-dm.org/mdedys/react-text-trimmer/status.svg)](https://david-dm.org/mdedys/react-text-trimmer)
[![devDependencies Status](https://david-dm.org/mdedys/react-text-trimmer/dev-status.svg)](https://david-dm.org/mdedys/react-text-trimmer?type=dev)
[![peerDependencies Status](https://david-dm.org/mdedys/react-text-trimmer/peer-status.svg)](https://david-dm.org/mdedys/react-text-trimmer?type=peer)

# react-text-trimmer

React component that trims overflowing multi line text and adds a specified tail

## Installation

Install from NPM:

```shell
yarn install react-text-trimmer
```

## Usage

### Props

`className` : _default_ : `empty string` CSS class name to add specific styling

`textTail` : _default_ : `...` String to append to end of trimmed text

`maxLines` : _default_ : `3` Number of lines to render before truncating text

### Example

```js
import Trimmer from "react-text-trim"

;<div className="my-text">
  <Trimmer maxLines={2} textTail="...">
    Some text to be truncated
  </Trimmer>
</div>
```

### Code Style

This repository is configured with [EditorConfig][editorconfig].

[npm-url]: https://npmjs.org/package/react-text-trimmer
[npm-image]: https://img.shields.io/npm/v/react-text-trimmer.png
[ci-url]: https://travis-ci.org/mdedys/react-text-trimmer
[ci-image]: https://img.shields.io/travis-ci/mdedys/react-text-trimmer.svg
[editorconfig]: http://editorconfig.org/
