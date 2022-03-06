# `eslint-strict-null-check`

[![NPM version][npm-image]][npm-url]

Eslint plugin that aims to reproduce strictNullCheck from tsconfig for easier migration and for projects that prefer to have it as a warning not an error.

# Installation

Install [`eslint`](https://www.github.com/eslint/eslint) and eslint-strict-null-check plugin locally.

```sh
$ npm install eslint eslint-strict-null-check --save-dev
```

# Configuration

Use [our preset](#recommended) to get reasonable defaults:

```json
  "plugins": [
    "strict-null-check"
  ],
  "rules": [
    "strict-null-check/all"
  ]
```

# License

`eslint-strict-null-check` is licensed under the [MIT License](https://opensource.org/licenses/mit-license.php).

[npm-url]: https://npmjs.org/package/eslint-plugin-react
[npm-image]: https://img.shields.io/npm/v/eslint-strict-null-check.svg
