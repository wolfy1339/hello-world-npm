# hello-world-npm

This is a simple npm package that demonstrates the [GitHub Package Registry](https://github.com/features/package-registry).

## Installation

Before installing, make sure to authenticate with GitHub Package Registry or using a `.npmrc` file. See "[Configuring npm for use with GitHub Package Registry](https://help.github.com/en/articles/configuring-npm-for-use-with-github-package-registry#authenticating-to-github-package-registry)."

`$ npm install @octo-org/hello-world-npm`

Or add this package to your `package.json` file:

```
"dependencies": {
    "@octo-org/hello-world-npm": "1.0.3"
  }
```

## Usage

```
const myPackage = require('@octo-org/hello-world-npm');
myPackage.helloWorld();
```
