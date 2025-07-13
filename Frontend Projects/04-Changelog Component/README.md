# Changelog Component

基于 [roadmap.sh Changelog Component 项目](https://roadmap.sh/projects/changelog-component) 的练习实现。

## 项目目标
- 使用 HTML + CSS 创建一个美观、响应式、可访问的 Changelog 组件。
- 熟悉 changelog 卡片、标签、时间戳等常见结构和样式。

## 页面与布局
- 单页面组件，采用卡片式分区布局，顶部有标题，下方为多条 changelog。
- 每条 changelog 包含版本号、日期、标签（如 New/Update/Release）、内容列表。
- 响应式设计，适配不同屏幕。
- 便于后续扩展内容和样式。

### 主要分区
- Changelog 标题
- 多条 changelog（每条含版本、日期、标签、内容）

## 结构与体验优化
- 语义化 HTML 标签（如 `<section>`, `<article>`, `<ul>`, `<span>` 等）
- `<head>` 包含 SEO meta 标签（title、description、keywords、author、robots）
- 结构与 [roadmap.sh 项目 mockup](https://assets.roadmap.sh/guest/changelog-component-1m86j.png) 一致
- 使用 CSS 文件美化布局，支持响应式
- **暗色模式**：自动适配系统主题
- **可访问性**：badge/标题/列表均支持键盘聚焦和屏幕阅读器
- **动画与细节**：卡片和 badge 带有 hover/focus 动画，体验流畅

## 如何使用
1. 直接在浏览器中打开 `index.html` 预览效果
2. 可根据需要修改 changelog 内容和样式

---

> 参考：[roadmap.sh Changelog Component 项目说明](https://roadmap.sh/projects/changelog-component) 