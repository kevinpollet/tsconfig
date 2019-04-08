# @kevinpollet/tsconfig &middot; [![Build Status](https://travis-ci.com/kevinpollet/tsconfig.svg?branch=master)](https://travis-ci.com/kevinpollet/tsconfig)

Shared TypeScript project configuration.

## Install

```bash
$ npm install --save-dev @kevinpollet/tsconfig
```

## Extend TypeScript configuration

```json
{
  "extends": "@kevinpollet/tsconfig.json",
  "compilerOptions": {
    // Override / Add config options
  },
  "include": ["src"]
}
```

👉 See https://www.typescriptlang.org/docs/handbook/tsconfig-json.html for available configuration options.

## License

See [LICENSE.md](./LICENSE.md)
