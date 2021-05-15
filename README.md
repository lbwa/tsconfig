# @lbwa/tsconfig

Shared TypeScript config.

## Installation

```bash
yarn add @lbwa/tsconfig typescript tslib -D
# npm i @lbwa/tsconfig typescript tslib -D
```

## Usage

In your project root `tsconfig.json`:

```json
{
  "extends": "@lbwa/tsconfig",
  "compilerOptions": {
    "outDir": "dist"
  }
}
```

Diagnosing the effective TypeScript configurations:

```bash
yarn tsc --showConfig
# npx tsc --showConfig
```

## License

[MIT](./LICENSE) © [Liu Bowen](https://github.com/lbwa)
