# Frost Stylelint Config

[![CI](https://github.com/frost-js/stylelint-config/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/frost-js/stylelint-config/actions/workflows/ci.yml)
[![npm version](https://img.shields.io/npm/v/%40fr0st/stylelint-config?style=flat-square)](https://www.npmjs.com/package/@fr0st/stylelint-config)
[![npm downloads](https://img.shields.io/npm/dm/%40fr0st/stylelint-config?style=flat-square)](https://www.npmjs.com/package/@fr0st/stylelint-config)
[![license](https://img.shields.io/github/license/frost-js/stylelint-config?style=flat-square)](./LICENSE)

Stylelint shareable config for the *Frost* style.

## Installation

```bash
npm i -D @fr0st/stylelint-config stylelint
```

## Usage

Create `stylelint.config.js`:

```js
export default {
    extends: ['@fr0st/stylelint-config'],
};
```

The shared config supports both CSS and SCSS. SCSS-specific rules are applied to `**/*.scss`.

## Compatibility

- Node `^20.19.0 || ^22.13.0 || >=24`
- Stylelint: `^17.6.0`
- File types: CSS and SCSS

## Development

```bash
npm test
npm run lint
```

## License

Frost Stylelint Config is released under the [MIT License](./LICENSE).
