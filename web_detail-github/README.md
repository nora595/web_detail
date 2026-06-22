# LINSY 商城 WEB 端交易链路 Demo

林氏家居 B2B 商城 WEB 端静态交互演示。

## GitHub Pages 部署

1. 将本目录**全部文件**上传到仓库**根目录**（与 `index.html` 同级）
2. 仓库 Settings → Pages → Source 选 **Deploy from a branch**
3. Branch 选 `main`，文件夹选 `/ (root)`，保存
4. 访问 `https://<用户名>.github.io/<仓库名>/`

> 必须包含 `.nojekyll`，否则 GitHub 可能只显示 README 空白页。

## 本地预览

双击 `index.html`，或：

```bash
npx serve -l 8765 .
```

默认路由：`#/detail/p1`（商品详情）

## 文件

| 文件 | 说明 |
|------|------|
| `index.html` | 入口 |
| `mall-trade-demo.js` | 页面逻辑与 mock 数据 |
| `mall-trade-demo.css` | 样式 |
| `mall-i18n.js` | 中英文 / USD·CNY |
