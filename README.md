# @handy-eco/eslint-config

> Common eslint configuration for Handy UI Projects

## Usage

#### Install

```bash
yarn add -D eslint prettier @handy-eco/eslint-config
```

#### Config `.eslintrc`

```json
{
  "extends": "@handy-eco/eslint-config"
}
```

### Without Prettier `.eslintrc`

If you do not want to use `prettier`, you can easily compose your own config:

```json
{
  "extends": [
    "@handy-eco/eslint-config/ecma",
    "@handy-eco/eslint-config/typescript",
    "@handy-eco/eslint-config/json"
  ]
}
```

### Usage with React `.eslintrc`

Vue Storefront `React` specific linting rules.

```json
{
  "extends": [
    "@handy-eco/eslint-config",
    "@handy-eco/eslint-config/react"
  ]
}
```

### Usage with Vue `.eslintrc`

Vue Storefront `Vue` specific linting rules.

```json
{
  "extends": [
    "@handy-eco/eslint-config",
    "@handy-eco/eslint-config/vue"
  ]
}
```

### Usage with Vue3 `.eslintrc`

Vue Storefront `Vue3` specific linting rules.

```json
{
  "extends": [
    "@handy-eco/eslint-config",
    "@handy-eco/eslint-config/vue3"
  ]
}
```

## Used rulesets & plugins

- [unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn)
- [no-secrets](https://github.com/nickdeis/eslint-plugin-no-secrets)
- [no-unsanitized](https://github.com/mozilla/eslint-plugin-no-unsanitized)
- [promise](https://github.com/eslint-community/eslint-plugin-promise)
- [sonarjs](https://github.com/SonarSource/eslint-plugin-sonarjs)
- [@microsoft/sdl](https://github.com/microsoft/eslint-plugin-sdl)
- [unused-imports](https://www.npmjs.com/package/eslint-plugin-unused-imports)
- [prettier](https://github.com/prettier/eslint-plugin-prettier)

