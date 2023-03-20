# @topplethenun/eslint-config

- Enables ESLint Recommended rules for JS
- Enables TypeScript ESLint Recommended rules for TS
  - Disables `require` rule for JS files
- Enables simple import sorting rules for JS/TS

## Usage

### Install

```shell
$ pnpm install -D @topplethenun/eslint-config
```

### Config `.eslintrc`

```json
{
  "extends": "@topplethenun"
}
```

### Add scripts to package.json

```json
{
  "scripts": {
    "lint": "eslint --format stylish --max-warnings 0 --cache .",
    "lint:fix": "eslint --format stylish --max-warnings 0 --cache . --fix"
  }
}
```

## License

[MIT](./LICENSE) License © 2023-PRESENT [Richard Harrah](https://github.com/ToppleTheNun)
