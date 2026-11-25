# site-alcohol-beverages

喝酒去酒类百科站，部署地址 `beverages.hejiu.org`。承载原主站识酒内容，共 1,560 个发布页。

- 正文来源：`world-alcohol-encyclopedia/beverages/`
- 应用：`apps/main/`（Astro 静态生成，包名 `@hejiu/site-beverages`）
- 共享工程：`site-alcohol-core` 的 `packages/ui`、`packages/build-tools`、`packages/contracts`
- 本域搜索：只索引本站内容；全站聚合搜索在主站 `hejiu.org`

## 命令

在 `implementation/` 工作区运行：

```text
npm run build:beverages
npm run build -w @hejiu/site-beverages
```
