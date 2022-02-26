# sientech frontend custom eslint rule base on vue2/vue3

## Usage


### Installation

require "eslint-plugin-vue@^8.2.0",please update vue2 project for correct version

```sh
yarn add -D @sientech/eslint-config-frontend eslint-plugin-vue
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
    '@sientech/frontend/lib/vue2-essential'
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
 - `@sientech/eslint-config-frontend/lib/eslint-base`: define custom eslint rules
 - `@sientech/eslint-config-frontend/lib/vue-base`: define custom vue rules
 - `@sientech/eslint-config-frontend/lib/base`: define custom vue & eslint rules
 - `@sientech/eslint-config-frontend/lib/vue2-essential`: base on `@sientech/eslint-config-frontend/lib/base` and vue-essential rules
 - `@sientech/eslint-config-frontend/lib/vue2-recommended`: base on `@sientech/eslint-config-frontend/lib/base` and vue-recommended rules
 - `@sientech/eslint-config-frontend/lib/vue3-base`: base on `@sientech/eslint-config-frontend/lib/base` and define custom vue3 rules
 - `@sientech/eslint-config-frontend/lib/vue3-essential`: base on `@sientech/eslint-config-frontend/lib/vue3-base` and vue3-essential rules
 - `@sientech/eslint-config-frontend/lib/vue3-recommended`: base on `@sientech/eslint-config-frontend/lib/vue3-base` and vue3-recommended rules

