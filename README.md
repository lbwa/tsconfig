# @lbwa/tsconfig

Shared TypeScript config.

## Installation

```bash
yarn add @lbwa/tsconfig typescript@^4.2.4 tslib@^2.2.0
# npm i @lbwa/tsconfig typescript@^4.2.4 tslib@^2.2.0
```

## Usage

In your project root `tsconfig.json`:

```json5
{
  extends: '@lbwa/tsconfig',
  compilerOptions: {
    outDir: 'dist' /* Redirect output structure to the directory. */,
    incremental: true,
    tsBuildInfoFile: 'dist/.tsbuildinfo'
  },
  exclude: ['dist', 'coverage']
}
```

Diagnosing the effective TypeScript configurations:

```bash
yarn tsc --showConfig
# npx tsc --showConfig
```

## License

[MIT](./LICENSE) © [Liu Bowen](https://github.com/lbwa)
