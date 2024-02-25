# eslint-config-dorakemon

## Installation

```
yarn add -D eslint prettier @dorakemon/eslint-config-dorakemon
```

## Setup

`.prettierc.json`

```json
{
  "semi": true,
  "trailingComma": "all",
  "singleQuote": false,
  "tabWidth": 2
}
```

`.eslintrc.cjs`

```javascript
module.exports = {
  root: true,
  env: { browser: true, es2020: true },
  extends: ["@dorakemon/eslint-config-dorakemon"],
  ignorePatterns: ["dist", ".eslintrc.cjs"],
};
```
