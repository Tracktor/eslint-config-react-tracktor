# eslint-config-react-tracktor

[![npm version](https://badge.fury.io/js/eslint-config-react-tracktor.svg)](https://badge.fury.io/js/eslint-config-react-tracktor)

A set of opinionated [ESLint](http://eslint.org) rules for react projects

- [Installation](#Installation)
- [Usage](#Usage)
- [Specific rules](#Specific-rules)
- [Read more](#Read-more)

## Installation

```console
yarn add eslint-config-react-tracktor -D
```

## Usage

Create a file named `.eslintrc` in your root project and extends config :

```json
{
  "extends": "eslint-config-react-tracktor",
  "rules": {
    "...": "..."
  },
  "overrides": "..."
}
```

## Specific rules

For better compatibility with generated api files, 
some rules are disabled inside `src/api` folder.

```json
{
  "files": "./src/api/**/*.ts",
  "rules": {
    "indent": "off",
    "no-duplicate-imports": "off",
    "sort-keys": "off",
    "no-redeclare": "off",
  }
}
```

## Read more

Read more about eslint rules here: http://eslint.org/docs/rules

## Convention

- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- [Versioning](https://semver.org/)
- [Conventional Commits](https://www.conventionalcommits.org)
