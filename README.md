```bash
npm i
npm run dev
# or
npm run build
```

ends with 

```
> react-query-4-next-example@0.1.0 build
> next build

info  - SWC minify release candidate enabled. https://nextjs.link/swcmin
info  - Linting and checking validity of types  
info  - Creating an optimized production build  
info  - Compiled successfully

> Build error occurred
Error: Cannot find module '../../../node_modules/use-sync-external-store/shim/index.js'
Require stack:
- /home/janfabian/dev/react-query-4-next-example/node_modules/react-query/build/cjs/packages/react-query/src/useSyncExternalStore.js
- /home/janfabian/dev/react-query-4-next-example/node_modules/react-query/build/cjs/packages/react-query/src/useQueries.js
- /home/janfabian/dev/react-query-4-next-example/node_modules/react-query/build/cjs/packages/react-query/src/index.js
- /home/janfabian/dev/react-query-4-next-example/.next/server/pages/index.js
- /home/janfabian/dev/react-query-4-next-example/node_modules/next/dist/server/require.js
- /home/janfabian/dev/react-query-4-next-example/node_modules/next/dist/server/load-components.js
- /home/janfabian/dev/react-query-4-next-example/node_modules/next/dist/build/utils.js
- /home/janfabian/dev/react-query-4-next-example/node_modules/next/dist/build/worker.js
- /home/janfabian/dev/react-query-4-next-example/node_modules/next/dist/compiled/jest-worker/processChild.js
    at Module._resolveFilename (node:internal/modules/cjs/loader:939:15)
    at Module._load (node:internal/modules/cjs/loader:780:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/home/janfabian/dev/react-query-4-next-example/node_modules/react-query/build/cjs/packages/react-query/src/useSyncExternalStore.js:15:1)
    at Module._compile (node:internal/modules/cjs/loader:1105:14)
    at Module._extensions..js (node:internal/modules/cjs/loader:1159:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Module._load (node:internal/modules/cjs/loader:827:12)
    at Module.require (node:internal/modules/cjs/loader:1005:19) {
  type: 'Error',
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/home/janfabian/dev/react-query-4-next-example/node_modules/react-query/build/cjs/packages/react-query/src/useSyncExternalStore.js',
    '/home/janfabian/dev/react-query-4-next-example/node_modules/react-query/build/cjs/packages/react-query/src/useQueries.js',
    '/home/janfabian/dev/react-query-4-next-example/node_modules/react-query/build/cjs/packages/react-query/src/index.js',
    '/home/janfabian/dev/react-query-4-next-example/.next/server/pages/index.js',
    '/home/janfabian/dev/react-query-4-next-example/node_modules/next/dist/server/require.js',
    '/home/janfabian/dev/react-query-4-next-example/node_modules/next/dist/server/load-components.js',
    '/home/janfabian/dev/react-query-4-next-example/node_modules/next/dist/build/utils.js',
    '/home/janfabian/dev/react-query-4-next-example/node_modules/next/dist/build/worker.js',
    '/home/janfabian/dev/react-query-4-next-example/node_modules/next/dist/compiled/jest-worker/processChild.js'
  ]
}

```