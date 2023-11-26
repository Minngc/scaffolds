# TS

涵盖执行 ts 所需的依赖。

## 配置项

- `readline-sync` 支持从终端的同步的数据读入

## 运行例

```bash
pnpm dev
pnpm start ./src/main.ts
```

## 注意事项

将 node.js 升级到新的 lts 版本（v20.9.0）后，旧 lts 版本（v18.18.0）的命令无法使用，目前还未找到非常好的解决方案。

若使用旧 lts 版本的 node.js，将 `package.json` 中的 `node --import ts-node/esm` 换为 `ts-node --esm`，将 `@tsconfig/node18` 换为 `@tsconfig/node18`，并将 `@types/node` 版本替换为 `v18.18.*` 即可。


