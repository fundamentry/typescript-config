# `@fundamentry/typescript-config`

Shareable and extensible TypeScript configurations.

## Installation

```sh
pnpm install -D @fundamentry/typescript-config
```

## Usage

Extend one of the provided presets from your project’s `tsconfig.json`:

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@fundamentry/typescript-config/common"
}
```

The configuration provides sensible defaults and can be freely customised by overriding compiler options or layering additional extends entries as needed.

## Changelog

Detailed changes for each release are documented in [CHANGELOG.md](https://github.com/fundamentry/typescript-config/blob/HEAD/CHANGELOG.md).
