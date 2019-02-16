# TEST AssemblyScript Performance

Compile with [AssemblyScript](https://github.com/AssemblyScript/assemblyscript) code written in **[TS](rotate.ts) _-> WASM_** and compare to pure [JS](test/rotate.js) solution on "hot-path" code.

### build istruction

```console
> npm i AssemblyScript/assemblyscript
> asc rotate.ts -b assemblyscript.wasm --validate -O3

OR SIMPLY:
> npm i  &&  npm start
```

Read more on this [article](https://developers.google.com/web/updates/2019/02/hotpath-with-wasm#assemblyscript) + original [code](https://gist.github.com/surma/0eb306fa9acc8bdf2f58150b2f1e82b4#file-rotate-ts) here!
