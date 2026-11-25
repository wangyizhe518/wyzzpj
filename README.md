# 王一喆 · 视觉设计作品集

个人视觉设计作品集网站，使用原生 HTML、CSS 和 JavaScript 构建，无需安装依赖或打包。

## 本地预览

直接打开 `index.html` 即可浏览。项目图片保存在 `assets/portfolio/`，项目详情中的局部作品素材保存在 `assets/portfolio/case-crops/`。

## 部署

网站为纯静态文件，无构建步骤。GitHub 仓库连接 Cloudflare Pages 后，推送到 `main` 分支会触发线上更新；线上地址为 `https://wyzzpj.pages.dev`。

项目卡片、详情文案和交互阶段集中在 `index.html` 底部的 `projects` 数组。原图经过单件裁切后保存在 `assets/portfolio/case-crops/`，详情页使用独立的交互浏览方式。

