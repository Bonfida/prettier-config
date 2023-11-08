# `@bonfida/prettier-config`

## Getting started

### 1. Installation

Using npm:

```sh
npm i @bonfida/prettier-config --save-dev
```

Using Yarn:

```sh
yarn add @bonfida/prettier-config --dev
```

### 2. Usage

#### Scenario 1 - Basic usage

Edit `package.json`:

```jsonc
{
  // ...
  "prettier": "@bonfida/prettier-config"
}
```

#### Scenario 2 - Overrides

If you want to override config, you need to use `.prettierrc.js` instead of `package.json` and edit it like that:

```js
import bonfidaPrettierConfig from '@bonfida/prettier-config';

export default {
  ...bonfidaPrettierConfig,
  semi: false,
};
```

That's it! 🎉

For more information read [Prettier Official Documentation](https://prettier.io/docs/en/configuration).
