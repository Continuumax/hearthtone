# HearthTone 官网（独立站）

HearthTone 官方网站，由 ContinuuMax（連續向限）维护。纯静态 HTML/CSS/JS，无构建依赖、无后端、无外部资源。

## 页面
- `index.html` — 首页（产品介绍、特性概览、CTA）
- `features.html` — 特性页
- `download.html` — 下载页（版本信息、系统要求、更新日志、百度网盘跳转确认）
- `privacy.html` — 隐私政策
- `terms.html` — 服务条款

## 说明
- 多语言：繁體中文（預設）/ 简体中文 / English (US) / English (UK)，右上角切换，记忆在 localStorage `continuumax_lang`
- Cookie 合规：仅一个偏好 Cookie `continuumax_consent`（180 天），无第三方追踪
- 图片存放在 `assets/img/`，页脚注明 Unsplash 图源
- 下载跳转百度网盘，带跳转确认弹窗
- 页脚含返回 ContinuuMax 主站的外链

## 部署
1. 本文件夹内容即站点根目录，可推到独立仓库或作为 `continuumax.github.io` 的子目录（如 `/hearthtone/`）。
2. GitHub Pages：Settings → Pages → 分支 `main`，目录选根目录。
3. 本地预览：`python -m http.server 8000`，访问 `http://localhost:8000/`。

`.nojekyll` 已包含，禁用 Jekyll 处理。

> AI生成
