# @a-2-c-2-anpm/consequatur-cumque-aperiam

[![NPM version][npm-img]][npm-url] [![Downloads][downloads-img]][npm-url]

Turns off all CSS and SCSS rules that are unnecessary or might conflict with Prettier (extends [`stylelint-config-prettier`](https://npmjs.org/package/stylelint-config-prettier)). This lets you use your favorite shareable config without letting its stylistic choices get in the way when using Prettier.

## Installation

Install `@a-2-c-2-anpm/consequatur-cumque-aperiam`:

```
npm install --save-dev @a-2-c-2-anpm/consequatur-cumque-aperiam
```

Then, append `@a-2-c-2-anpm/consequatur-cumque-aperiam` to the [`extends` array](https://stylelint.io/user-guide/configuration/#extends) in your `.stylelintrc.*` file. Make sure to put it **last,** so it will override other configs.

```js
{
  "extends": [
    // other configs ...
    "@a-2-c-2-anpm/consequatur-cumque-aperiam"
  ]
}
```

## CLI helper tool

`@a-2-c-2-anpm/consequatur-cumque-aperiam` is shipped with a little CLI tool to help you check if your configuration contains any rules that are in conflict with Prettier.

In order to execute the CLI tool, first add a script for it to `package.json`:

```json
{
  "scripts": {
    "stylelint-scss-check": "@a-2-c-2-anpm/consequatur-cumque-aperiam-check"
  }
}
```

Then run `npm run stylelint-scss-check`.

## Attribution

- Inspired by [`eslint-config-prettier`](https://npm.im/eslint-config-prettier).
- CLI helper inspired by [`tslint-config-prettier`](https://github.com/alexjoverm/tslint-config-prettier).
- Original disabled ruleset copied from [`prettier-stylelint`](https://npm.im/prettier-stylelint).

----

[MIT](LICENSE.md)

[downloads-img]: https://img.shields.io/npm/dm/@a-2-c-2-anpm/consequatur-cumque-aperiam.svg?style=flat-square
[npm-img]:       https://img.shields.io/npm/v/@a-2-c-2-anpm/consequatur-cumque-aperiam.svg?style=flat-square
[npm-url]:       https://npmjs.org/package/@a-2-c-2-anpm/consequatur-cumque-aperiam
