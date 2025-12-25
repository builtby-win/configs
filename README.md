# @builtby.win/configs

Shared Biome configuration for builtby.win projects.

## Usage

1. Install the package:
```bash
pnpm add -D @builtby.win/configs
```

2. Create a `biome.json` in your project:
```json
{
  "$schema": "https://biomejs.dev/schemas/1.9.4/schema.json",
  "extends": ["@builtby.win/configs"]
}
```

3. Add scripts to your `package.json`:
```json
{
  "scripts": {
    "format": "biome format --write .",
    "lint": "biome lint .",
    "check": "biome check --write ."
  }
}
```

## Configuration

This config includes:
- 2-space indentation
- Single quotes for JS, double quotes for JSX
- Line width of 100
- Semicolons as needed
- Trailing commas everywhere
- Comprehensive linting rules for TypeScript and React
