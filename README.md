# electron-forge-plugin-prune-prebuilds

Prune unused native prebuilds from your packaged Electron app.

```
npm i -D electron-forge-plugin-prune-prebuilds
```

## Requirements

- Electron Forge 8 (this package is ESM-only, matching Forge 8)
- Node.js >= 22.13.0

## Usage

```js
export default {
  // ...
  plugins: [
    {
      name: 'electron-forge-plugin-prune-prebuilds',
      config: {}
    }
  ]
}
```

## License

Apache-2.0
