# prettier-config

My personal prettier config

## Installation

### npm

```
npm install prettier @darwintantuco/prettier-config --save-dev
```

### yarn

```
yarn add prettier @darwintantuco/prettier-config --dev
```

## Usage

Add prettier config in `package.json`

```json
{
  "prettier": "@darwintantuco/prettier-config",
  "scripts": {
    "prettier:check": "prettier --list-different 'css/**/*.{css,scss}' 'js/**/*.{js,jsx,ts,tsx}'",
    "prettier:fix": "prettier --write 'css/**/*.{css,scss}' 'js/**/*.{js,jsx,ts,tsx}'"
  }
}
```

## License

MIT
