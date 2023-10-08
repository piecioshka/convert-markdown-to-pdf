# convert-markdown-to-pdf

[![node version](https://img.shields.io/node/v/convert-markdown-to-pdf.svg)](https://www.npmjs.com/package/convert-markdown-to-pdf)
[![npm version](https://badge.fury.io/js/convert-markdown-to-pdf.svg)](https://badge.fury.io/js/convert-markdown-to-pdf)
[![downloads count](https://img.shields.io/npm/dt/convert-markdown-to-pdf.svg)](https://www.npmjs.com/package/convert-markdown-to-pdf)

:hammer: Convert Markdown file to PDF.

> Give a ⭐️ if this project helped you!

## Features

* :white_check_mark: Build PDF file form Markdown file
* :white_check_mark: Generate PDF file in the same directory as Markdown file
* :white_check_mark: Use one of built-in themes or custom pass custom path to theme file

## Install

```bash
npm install -g convert-markdown-to-pdf
```

## Usage

```js
const { buildPDF } = require('convert-markdown-to-pdf');
buildPDF({
  source: '/tmp/source.md',
  target: '/tmp/document.pdf'
});
```

## CLI

### :arrow_right: Use case: Regular usage

```bash
convert-markdown-to-pdf /tmp/source.md
```

### :arrow_right: Use case: Changing theme

```bash
convert-markdown-to-pdf /tmp/source.md -t ~/projects/convert-markdown-to-pdf-themes/dark.css
convert-markdown-to-pdf /tmp/source.md --theme ~/projects/convert-markdown-to-pdf-themes/orange.css
```

## Unit tests

```bash
npm test
```

## Code coverage

```bash
npm run coverage
```

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />
Feel free to check [issues page](/issues/).

## License

[The MIT License](http://piecioshka.mit-license.org) @ 2018-2023
