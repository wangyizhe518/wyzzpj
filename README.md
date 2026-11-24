# 王一喆 · 视觉设计作品集

个人视觉设计作品集网站，使用原生 HTML、CSS 和 JavaScript 构建，无需安装依赖或打包。

## 本地预览

直接打开 `index.html` 即可浏览。项目图片保存在 `assets/portfolio/`，项目详情中的局部作品素材保存在 `assets/portfolio/case-crops/`。

## 部署

推送到 `main` 分支后，GitHub Actions 会自动发布到 GitHub Pages。工作流定义在 `.github/workflows/pages.yml`。

项目卡片、详情文案和交互阶段集中在 `index.html` 底部的 `projects` 数组。邮箱当前使用作品集 PDF 中的地址，发布前可直接替换。
