# 英语精读 · 网站

这个仓库只放**打包好的网页**（由 Claude 打包后推上来），源代码在私有仓库里，不要在这里手改。

- **Underline App 原型**（按设计稿做的真实 App，演示数据）：https://yichengye34.github.io/english-reading-web/underline/
- 设计原型（可点的完整 App）：https://yichengye34.github.io/english-reading-web/prototype/
- 全部画板：https://yichengye34.github.io/english-reading-web/prototype/boards.html
- APP 网页版：https://yichengye34.github.io/english-reading-web/

## Underline（/underline/）

- `underline/` 是 Underline App 的网页版正式包（`WEB_BASE_URL=/english-reading-web/underline npm run build:web` 的 dist）。
- 直接打开 `/underline/vocab` 这类深层网址时，GitHub Pages 返回根目录的 `404.html`；它最前面有一小段脚本，
  把 `/underline/` 下的网址跳回 `/underline/?__path=原路径`，Underline 的页面再把地址栏还原。
  **以后重新发布根目录的旧版网页时，记得保留 404.html 开头这段脚本。**
