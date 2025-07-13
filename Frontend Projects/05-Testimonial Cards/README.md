# Testimonial Cards

基于 [roadmap.sh Testimonial Cards 项目](https://roadmap.sh/projects/testimonial-cards) 的练习实现。

## 项目目标
- 使用 HTML + CSS 创建一组美观、响应式、可访问的 Testimonial Cards 组件
- 实现错落有致的布局效果，通过背景色差异创造视觉层次
- 熟悉现代 CSS Grid 布局和卡片设计最佳实践

## 页面与布局
- 单页面组件，采用错落有致的网格布局
- 顶部有标题，下方为多条 testimonial 卡片
- 每条 testimonial 包含头像、用户名、职位、评价内容
- 通过背景色差异创造视觉错落感
- 响应式设计，适配不同屏幕尺寸

### 主要分区
- Testimonial 标题
- 多条 testimonial 卡片（错落布局）

## 结构与体验优化
- 语义化 HTML 标签（如 `<section>`, `<article>`, `<img>`, `<span>` 等）
- `<head>` 包含 SEO meta 标签（title、description、keywords、author、robots）
- 使用 CSS Grid 实现错落有致的布局
- **暗色模式**：自动适配系统主题
- **可访问性**：头像alt、标题tabindex、卡片role等
- **动画与细节**：卡片hover动画、头像圆形、Google Fonts优化字体

### 卡片类型
- **Featured Cards**: 蓝色渐变背景，突出显示重要内容
- **Wide Cards**: 2x1 网格，横向跨越两列
- **Standard Cards**: 1x1 网格，白色背景

### 错落设计特点
- **背景色差异**：Featured 卡片使用浅蓝色渐变背景
- **视觉层次**：其他卡片保持白色背景，形成清晰对比
- **突出重要内容**：第一个卡片通过颜色和尺寸突出显示

### 响应式设计
- **桌面端 (1200px+)**: 自适应网格，最多4列
- **平板端 (900px-1200px)**: 自适应网格，最多3列
- **手机端 (600px-900px)**: 自适应网格，最多2列
- **小屏手机 (<600px)**: 单列布局

## 如何使用
1. 直接在浏览器中打开 `index.html` 预览效果
2. 可根据需要修改 testimonial 内容和样式
3. 调整 CSS 中的网格参数来改变布局密度

---

> 参考：[roadmap.sh Testimonial Cards 项目说明](https://roadmap.sh/projects/testimonial-cards) 