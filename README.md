# mocha-cli

[![npm version](https://img.shields.io/npm/v/mocha-cli.svg)](https://www.npmjs.com/package/mocha-cli)
[![Downloads/month](https://img.shields.io/npm/dm/mocha-cli.svg)](https://www.npmjs.com/package/mocha-cli)
[![Dependency Status](https://david-dm.org/halkeye/mocha-cli.svg)](https://david-dm.org/halkeye/mocha-cli)

The local [mocha](https://github.com/mochajs/mocha) executor.

## Installation

```
> npm install -g mocha-cli
```

**Note:**

- The `mocha` module must not be installed into global.
- This module must be installed into global.

## Usage

First, please install the `mocha` module in local.

```
> npm install --save-dev mocha
```

Next, please do `mocha`.

```
> mocha 
```

This command executes the global `mocha-cli`, then it finds and executes the local `mocha`.

That's all. Enjoy!


PS. Copied heavily from https://github.com/mysticatea/eslint-cli
