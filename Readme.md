# Monorepo with TypeScript

```
yarn
cd servers/api
yarn run dev
```

This is a possible strategy to gradually migrate a project from `JS` with `yarn workspaces` to `TypeScript`.

Basically, we circumvent the `TypeScript` module loader form loading packages from the `node_modules` folder, by adding a `paths` config to `./tsconfig.json`.