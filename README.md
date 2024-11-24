# @lucaschrng/eslint

My ESLint preset.

## Features

This preset includes the following rules:

- **Semi-colons**: Always required (`semi: ["error", "always"]`).
- **Quotes**: Single quotes only (`quotes: ["error", "single"]`).
- **Indentation**: 2 spaces (`indent: ["error", 2]`).
- **No trailing spaces**: Disallowed (`no-trailing-spaces: "error"`).
- **No multiple empty lines**: Disallowed (`no-multiple-empty-lines: "error"`).
- **No multiple spaces**: Disallowed (`no-multi-spaces: "error"`).
- **Object curly spacing**: Spaces required (`object-curly-spacing: ["error", "always"]`).
- **End of line**: Always required (`eol-last: ["error", "always"]`).
- **Comma dangles**: Required in multiline structures (`comma-dangle: ["error", "always-multiline"]`).

## Installation

You can install the preset using your preferred package manager.

### Using npm
```bash
npm install @lucaschrng/eslint --save-dev
```

### Using pnpm
```bash
pnpm add @lucaschrng/eslint --save-dev
```

### Using yarn
```bash
yarn add @lucaschrng/eslint --dev
```

## Usage

To use this preset in your project, extend it in your ESLint configuration file. This preset works with `.eslintrc`, `eslint.config.js`, or other ESLint-supported configuration formats.

### Using `.eslintrc.json`
Create or update `.eslintrc.json` in the root of your project:

```json
{
  "extends": ["@lucaschrng/eslint"]
}
```

### Using `eslint.config.js`
Create or update `eslint.config.js` in the root of your project:

```javascript
export default [
  {
    extends: ["@lucaschrng/eslint"]
  }
];
```
