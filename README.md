# prettier-config

![badge](https://github.com/fiahfy/prettier-config/workflows/Node.js%20Package/badge.svg)

> My prettier config.

## Installation

```bash
npm install @fiahfy/prettier-config -D
```

## Usage

Edit `package.json`

```js
{
  // ...
  "prettier": "@fiahfy/prettier-config"
}
```

Or edit `.prettierrc.js`

```js
const config = require("@fiahfy/prettier-config");

module.exports = {
  ...config,
  // ...
};
```
