# eslint-config-react

A set of opinionated ESLint (http://eslint.org) rules (all rules included) for React projects

## Installation

```console
npm install git+https://github.com/Tracktor/eslint-config-react --save-dev
```

or 

```console
yarn add git+https://github.com/Tracktor/eslint-config-react -D
```

## Usage

Create a file named `.eslintrc` in your project and extends config :

```json
{
  "extends": "eslint-config-react",
  "rules": {
    "..." : "..."
  }
}
```

## Read more

Read more about all the rules here: http://eslint.org/docs/rules/

## Changelog

### 1.2.0
- Reduce printWidth prettier

### 1.1.1
- version

### 1.1.0
- Update printWidth prettier
- Add override rules for next.js app