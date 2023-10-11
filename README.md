# eslint-config-import-typescript

settings for eslint-plugin-import 

## Getting started

install using `npm`

```sh
npm install --save-dev eslint-config-import-typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint eslint-import-resolver-typescript eslint-plugin-import
```

install using `pnpm`

```sh
pnpm add --save-dev eslint-config-import-typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint eslint-import-resolver-typescript eslint-plugin-import
```

## .eslintrc.cjs

```javascript
module.exports = {
  extends: [
    "eslint:recommended",
    "plugin:@typescript-eslint/recommended",
    "eslint-config-import-typescript"
  ]
}
```
