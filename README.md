# shelter-zone custom eslint rule base

## Usage


### Installation

```sh
yarn add -D @shelter-zone/eslint-config-proladon
```

### Configuration

Example `.eslintrc.js`:

```js
module.exports = {
  root: true,
  env: {
    node: true
  },
  extends: [
    '@shelter-zone/frontend/lib/eslintTypescript'
  ],
  parserOptions: {
    ecmaVersion: 2020
  },
  globals: {
  },
  rules: {

  }
}
```

available extends:
 - `@shelter-zone/eslint-config-proladon/lib/eslint-base`: define custom eslint rules
 - `@shelter-zone/eslint-config-proladon/lib/vue-base`: define custom vue rules
 - `@shelter-zone/eslint-config-proladon/lib/base`: define custom vue & eslint rules
 - `@shelter-zone/eslint-config-proladon/lib/vue2-essential`: base on `@shelter-zone/eslint-config-proladon/lib/base` and vue-essential rules
 - `@shelter-zone/eslint-config-proladon/lib/vue2-recommended`: base on `@shelter-zone/eslint-config-proladon/lib/base` and vue-recommended rules
 - `@shelter-zone/eslint-config-proladon/lib/vue3-base`: base on `@shelter-zone/eslint-config-proladon/lib/base` and define custom vue3 rules
 - `@shelter-zone/eslint-config-proladon/lib/vue3-essential`: base on `@shelter-zone/eslint-config-proladon/lib/vue3-base` and vue3-essential rules
 - `@shelter-zone/eslint-config-proladon/lib/vue3-recommended`: base on `@shelter-zone/eslint-config-proladon/lib/vue3-base` and vue3-recommended rules

