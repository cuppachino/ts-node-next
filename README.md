# ts-node-next
🔥 Blazing TS + NodeNext template

## Scripts
| alias | description | command |
|-|:-:|:-|
| dev   |  watch the `src` folder and reload on change. | `nodemon --watch src --exec "ts-node-esm ./src/index.ts"` |
| build:swc | transpile once with swc | `ts-node ./src/index.ts` |
| build:tsc | build the project using the typescript compiler | `tsc --build --clean && tsc` |
| build:clean | removes ts-generated files from the `dist` folder | `tsc --build --clean` |
| build:start | execute `tsc` build with node | `node ./dist/index.js` |
```    
