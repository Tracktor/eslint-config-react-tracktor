# eslint-config-react

A set of opinionated [ESLint](http://eslint.org) rules (all rules included) for React projects

- [Installation](#Installation)
- [Usage](#Usage)
- [Read more](#Read-more)

## Installation

```console
yarn add git+https://github.com/Tracktor/eslint-config-react -D
```

Specific version can be installed

```console
yarn add git+https://github.com/Tracktor/eslint-config-react#v1.0.0 -D
```

## Usage

Create a file named `.eslintrc` in your root project and extends config :

```json
{
  "extends": "eslint-config-react",
  "rules": {
    "..." : "..."
  },
  "overrides": "..."
}
```

## Read more

Read more about all the rules here: http://eslint.org/docs/rules/

## Convention
- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- [Versioning](https://semver.org/)
- [Conventional Commits](https://www.conventionalcommits.org)
