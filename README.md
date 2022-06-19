# Typescript

Use ts-node with esm `--loader ts-node/esm`
Use `import test from './fileTest'` instead of `import test from './fileTest.ts'` with `--experimental-specifier-resolution=node`

Use `--loader ./loader.js` to use a custom loader with is equivalent to es-node/esm loader but works with tsconfig-paths

https://github.com/TypeStrong/ts-node/pull/1585