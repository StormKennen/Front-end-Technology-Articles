# ⚡ 性能优化与监控精选

> 核心 Web 指标、渲染优化、Bundle 分析、性能监控

**难度**: ⭐⭐⭐⭐⭐ 高级前端

---

## 📌 核心指标

### Web Vitals 完全指南

- **链接**: [Web Vitals](https://web.dev/vitals/)
- **来源**: Google web.dev
- **难度**: ⭐⭐⭐⭐
- **阅读时间**: 约 30 分钟
- **标签**: #WebVitals #性能 #核心指标
- **简介**: LCP、FID、CLS 等核心 Web 性能指标详解和优化方法
- **推荐理由**: Google 官方标准，SEO 和用户体验的核心指标

### Performance API 实战

- **链接**: [Performance API](https://developer.mozilla.org/zh-CN/docs/Web/API/Performance)
- **来源**: MDN
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #Performance #API #监控
- **简介**: 使用 Performance API 进行细粒度性能测量
- **推荐理由**: 浏览器原生 API，精确性能数据采集

---

## 🚀 渲染优化

### Critical Rendering Path 优化

- **链接**: [Critical Rendering Path](https://web.dev/critical-rendering-path/)
- **来源**: Google web.dev
- **难度**: ⭐⭐⭐⭐⭐
- **阅读时间**: 约 45 分钟
- **标签**: #CRP #渲染 #优化
- **简介**: 关键渲染路径优化，提升首屏加载速度
- **推荐理由**: 深入浏览器渲染原理，从根本上优化性能

### React 性能优化

- **链接**: [React Performance Best Practices](https://react.dev/learn/render-and-commit)
- **来源**: React 官方
- **难度**: ⭐⭐⭐⭐
- **标签**: #React #性能 #memo
- **简介**: React 应用性能优化技巧，包括 memo、useMemo、代码分割
- **推荐理由**: React 官方最佳实践，避免常见性能陷阱

### 虚拟列表与懒加载

- **链接**: [Virtual Scrolling](https://web.dev/virtualize-lists-with-webpack-and-react/)
- **来源**: Google web.dev
- **难度**: ⭐⭐⭐⭐
- **标签**: #虚拟列表 #懒加载 #大数据
- **简介**: 大数据列表的虚拟滚动和懒加载技术
- **推荐理由**: 处理大量数据时的必备优化技术

---

## 📦 Bundle 优化

### Webpack Bundle 分析

- **链接**: [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer)
- **来源**: GitHub
- **难度**: ⭐⭐⭐
- **标签**: #Webpack #Bundle #分析
- **简介**: 可视化分析 Webpack 打包结果，找出体积过大的模块
- **推荐理由**: 直观发现包体积问题，针对性优化

### Tree Shaking 最佳实践

- **链接**: [Tree Shaking Guide](https://developers.google.com/web/fundamentals/performance/optimizing-javascript/tree-shaking)
- **来源**: Google Developers
- **难度**: ⭐⭐⭐⭐
- **标签**: #TreeShaking #优化 #ESModule
- **简介**: 利用 Tree Shaking 移除未使用代码，减小包体积
- **推荐理由**: 现代构建工具必备优化手段

### Code Splitting 策略

- **链接**: [Code Splitting](https://webpack.js.org/guides/code-splitting/)
- **来源**: Webpack 官方
- **难度**: ⭐⭐⭐⭐
- **标签**: #CodeSplitting #懒加载 #优化
- **简介**: 代码分割策略，按需加载提升首屏速度
- **推荐理由**: 大型应用必备的优化技术

---

## 🖼️ 资源优化

### 图片优化完全指南

- **链接**: [Image Optimization](https://web.dev/fast/#optimize-your-images)
- **来源**: Google web.dev
- **难度**: ⭐⭐⭐
- **标签**: #图片 #优化 #WebP
- **简介**: 图片格式选择、压缩、懒加载等优化技术
- **推荐理由**: 图片通常占页面体积最大，优化效果显著

### 字体加载优化

- **链接**: [Font Loading Strategy](https://web.dev/optimize-webfont-loading/)
- **来源**: Google web.dev
- **难度**: ⭐⭐⭐⭐
- **标签**: #字体 #加载 #优化
- **简介**: Web 字体加载策略，避免 FOIT/FOUT 问题
- **推荐理由**: 提升文本渲染体验，避免闪烁

### CDN 与缓存策略

- **链接**: [CDN and Caching](https://web.dev/http-cache/)
- **来源**: Google web.dev
- **难度**: ⭐⭐⭐⭐
- **标签**: #CDN #缓存 #HTTP
- **简介**: CDN 选择和 HTTP 缓存策略配置
- **推荐理由**: 利用缓存大幅减少重复请求

---

## 📊 性能监控

### 实时性能监控方案

- **链接**: [Real User Monitoring](https://web.dev/user-centric-performance-metrics/)
- **来源**: Google web.dev
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #RUM #监控 #真实用户
- **简介**: 真实用户性能监控 (RUM) 方案设计和实施
- **推荐理由**: 了解真实用户性能体验，而非实验室数据

### Performance Observer API

- **链接**: [Performance Observer](https://developer.mozilla.org/zh-CN/docs/Web/API/PerformanceObserver)
- **来源**: MDN
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #PerformanceObserver #API #监控
- **简介**: 使用 Performance Observer 监听性能事件
- **推荐理由**: 异步性能数据采集，不影响主线程

### 性能告警与阈值

- **链接**: [Performance Budgets](https://web.dev/performance-budgets-101/)
- **来源**: Google web.dev
- **难度**: ⭐⭐⭐⭐
- **标签**: #性能预算 #告警 #阈值
- **简介**: 设置性能预算和告警阈值，持续监控性能
- **推荐理由**: 建立性能基线，防止性能退化

---

## 🔧 工具链

### Lighthouse CI

- **链接**: [Lighthouse CI](https://github.com/GoogleChrome/lighthouse-ci)
- **来源**: Google
- **难度**: ⭐⭐⭐⭐
- **标签**: #Lighthouse #CI #自动化
- **简介**: 在 CI 流程中集成 Lighthouse 性能测试
- **推荐理由**: 自动化性能回归检测

### WebPageTest

- **链接**: [WebPageTest](https://www.webpagetest.org/)
- **来源**: WebPageTest
- **难度**: ⭐⭐⭐
- **标签**: #测试 #性能 #对比
- **简介**: 多地点、多浏览器的性能测试平台
- **推荐理由**: 全球节点测试，对比竞品性能

### Chrome DevTools Performance

- **链接**: [Performance Panel](https://developer.chrome.com/docs/devtools/performance/)
- **来源**: Chrome DevTools
- **难度**: ⭐⭐⭐⭐
- **标签**: #DevTools #性能 #分析
- **简介**: 使用 Chrome DevTools Performance 面板分析性能
- **推荐理由**: 本地开发必备的性能分析工具

---

## 📈 性能优化清单

### 加载性能

- [ ] 启用 Gzip/Brotli 压缩
- [ ] 配置 HTTP 缓存策略
- [ ] 使用 CDN 分发静态资源
- [ ] 图片格式优化 (WebP/AVIF)
- [ ] 懒加载非关键资源
- [ ] 预加载关键资源 (preload/prefetch)

### 渲染性能

- [ ] 减少重排重绘
- [ ] 使用 CSS transform 代替位置变化
- [ ] 避免布局抖动
- [ ] 虚拟列表优化长列表
- [ ] 防抖节流高频事件

### JavaScript 性能

- [ ] 代码分割按需加载
- [ ] Tree Shaking 移除死代码
- [ ] Web Worker 处理重计算
- [ ] 避免内存泄漏
- [ ] 使用 requestAnimationFrame 优化动画

---

## 🎯 性能目标建议

| 指标 | 良好 | 需要改进 | 差 |
|------|------|----------|-----|
| LCP (最大内容绘制) | <2.5s | 2.5-4.0s | >4.0s |
| FID (首次输入延迟) | <100ms | 100-300ms | >300ms |
| CLS (累计布局偏移) | <0.1 | 0.1-0.25 | >0.25 |
| TTI (可交互时间) | <3.8s | 3.8-7.3s | >7.3s |
| TBT (总阻塞时间) | <200ms | 200-600ms | >600ms |

---

<div align="center">

**性能优化是持续的过程，不是一次性任务** ⚡

[返回主页](../README.md)

</div>
