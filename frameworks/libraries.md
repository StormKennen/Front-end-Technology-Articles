# 📦 前端常用库精选

> 解决具体问题的成熟库推荐

**难度**: ⭐⭐⭐⭐ 中高级前端

---

## 📌 按场景分类

### HTTP 请求

| 库 | 用途 | 特点 | 链接 |
|------|------|------|------|
| **axios** | HTTP 客户端 | 功能全面、拦截器 | [axios-http.com](https://axios-http.com/) |
| **ky** | HTTP 客户端 | 轻量、基于 Fetch | [github.com/sindresorhus/ky](https://github.com/sindresorhus/ky) |
| **swr** | 数据请求 | React Hooks、自动缓存 | [swr.vercel.app](https://swr.vercel.app/) |
| **react-query** | 数据请求 | 强大缓存、乐观更新 | [tanstack.com/query](https://tanstack.com/query) |

**推荐文章：**
- [axios 拦截器实战](https://juejin.cn/post/6844904092640837645) - 请求/响应拦截、错误处理
- [react-query 完全指南](https://juejin.cn/post/6953149562107363342) - 服务端状态管理

---

### 状态管理

| 库 | 框架 | 特点 | 链接 |
|------|------|------|------|
| **Redux Toolkit** | React | 官方推荐、简化 Redux | [redux-toolkit.js.org](https://redux-toolkit.js.org/) |
| **Zustand** | React | 轻量、简单、无样板代码 | [github.com/pmndrs/zustand](https://github.com/pmndrs/zustand) |
| **Jotai** | React | 原子化状态管理 | [jotai.org](https://jotai.org/) |
| **Pinia** | Vue | Vue 3 官方推荐 | [pinia.vuejs.org](https://pinia.vuejs.org/) |
| **MobX** | React/Vue | 响应式、简洁 | [mobx.js.org](https://mobx.js.org/) |

**推荐文章：**
- [Zustand 使用指南](https://juejin.cn/post/6896924695322689549) - 比 Redux 更简单
- [Pinia vs Vuex](https://juejin.cn/post/6961714845313024036) - 为什么选择 Pinia

---

### 路由管理

| 库 | 框架 | 特点 | 链接 |
|------|------|------|------|
| **React Router** | React | 官方路由、声明式 | [reactrouter.com](https://reactrouter.com/) |
| **Vue Router** | Vue | 官方路由、功能全面 | [router.vuejs.org](https://router.vuejs.org/zh/) |
| **Next.js Router** | React | 文件系统路由、SSR | [nextjs.org](https://nextjs.org/) |
| **Nuxt Router** | Vue | 文件系统路由、SSR | [nuxt.com](https://nuxt.com/) |

**推荐文章：**
- [React Router v6 迁移指南](https://juejin.cn/post/6884404561133510664) - v6 新特性
- [Vue Router 4 实战](https://juejin.cn/post/6953149562107363342) - 导航守卫、懒加载

---

### 表单处理

| 库 | 框架 | 特点 | 链接 |
|------|------|------|------|
| **React Hook Form** | React | 性能好、Hooks API | [react-hook-form.com](https://react-hook-form.com/) |
| **Formik** | React | 流行、功能全面 | [formik.org](https://formik.org/) |
| **VeeValidate** | Vue | 验证强大、易上手 | [vee-validate.logaretm.com](https://vee-validate.logaretm.com/) |
| **Formily** | React/Vue | 阿里出品、复杂表单 | [formilyjs.org](https://formilyjs.org/) |

**推荐文章：**
- [React Hook Form 实战](https://juejin.cn/post/6844903501789691918) - 表单验证、性能优化
- [Formily 复杂表单方案](https://juejin.cn/post/6854573179354087437) - 企业级表单

---

### UI 组件库

#### React

| 库 | 特点 | 链接 |
|------|------|------|
| **Ant Design** | 企业级、完整 | [ant.design](https://ant.design/) |
| **Material-UI** | Material Design | [mui.com](https://mui.com/) |
| **Chakra UI** | 易用、可访问性好 | [chakra-ui.com](https://chakra-ui.com/) |
| **Headless UI** | 无样式、完全可控 | [headlessui.com](https://headlessui.com/) |

#### Vue

| 库 | 特点 | 链接 |
|------|------|------|
| **Element Plus** | Element UI 升级版 | [element-plus.org](https://element-plus.org/) |
| **Ant Design Vue** | Ant Design Vue 版 | [antdv.com](https://antdv.com/) |
| **Naive UI** | TypeScript 支持好 | [naiveui.com](https://www.naiveui.com/) |
| **Vant** | 移动端组件库 | [vant-ui.github.io](https://vant-ui.github.io/vant/) |

**推荐文章：**
- [Ant Design 最佳实践](https://juejin.cn/post/6896924695322689549) - 企业级 UI 方案
- [Headless UI 完全指南](https://juejin.cn/post/6953149562107363342) - 自定义 UI 组件

---

### 日期时间

| 库 | 用途 | 特点 | 链接 |
|------|------|------|------|
| **dayjs** | 日期处理 | 轻量、API 友好 | [day.js.org](https://day.js.org/) |
| **date-fns** | 日期处理 | 函数式、Tree-shaking | [date-fns.org](https://date-fns.org/) |
| **Luxon** | 日期处理 | Moment 作者新作 | [moment.github.io/luxon](https://moment.github.io/luxon/) |
| **FullCalendar** | 日历组件 | 功能强大 | [fullcalendar.io](https://fullcalendar.io/) |

**推荐文章：**
- [dayjs 常用 API](https://juejin.cn/post/6844903501789691918) - 日期格式化、计算

---

### 图表可视化

| 库 | 用途 | 特点 | 链接 |
|------|------|------|------|
| **ECharts** | 图表 | 百度出品、功能强大 | [echarts.apache.org](https://echarts.apache.org/) |
| **AntV** | 可视化 | 阿里出品、系列全 | [antv.vision](https://antv.vision/) |
| **Chart.js** | 图表 | 简单、轻量 | [chartjs.org](https://www.chartjs.org/) |
| **Recharts** | 图表 (React) | 基于 D3、React 友好 | [recharts.org](https://recharts.org/) |
| **Vue-ECharts** | 图表 (Vue) | ECharts Vue 封装 | [github.com/ecomfe/vue-echarts](https://github.com/ecomfe/vue-echarts) |
| **D3.js** | 可视化 | 强大灵活、学习曲线陡 | [d3js.org](https://d3js.org/) |

**推荐文章：**
- [ECharts 进阶技巧](https://juejin.cn/post/6884404561133510664) - 自定义系列、性能优化
- [D3.js 入门教程](https://juejin.cn/post/6896924695322689549) - 数据驱动文档

---

### 动画

| 库 | 用途 | 特点 | 链接 |
|------|------|------|------|
| **Framer Motion** | 动画 (React) | 声明式、强大 | [framer.com/motion](https://www.framer.com/motion/) |
| **GSAP** | 动画 | 专业级、性能高 | [greensock.com/gsap](https://greensock.com/gsap/) |
| **Anime.js** | 动画 | 轻量、易用 | [animejs.com](https://animejs.com/) |
| **Lottie** | 动画 | AE 导出、JSON 格式 | [airbnb.io/lottie](https://airbnb.io/lottie/) |
| **Vue Transition** | 动画 (Vue) | 内置、简单 | [cn.vuejs.org/guide/built-ins/transition](https://cn.vuejs.org/guide/built-ins/transition.html) |

**推荐文章：**
- [Framer Motion 实战](https://juejin.cn/post/6953149562107363342) - React 动画最佳实践
- [GSAP 动画教程](https://juejin.cn/post/6844903501789691918) - 时间轴、缓动函数

---

### 工具函数

| 库 | 用途 | 特点 | 链接 |
|------|------|------|------|
| **lodash** | 工具函数 | 功能全面、经典 | [lodash.com](https://lodash.com/) |
| **lodash-es** | 工具函数 | ES Module 版本 | [lodash.com](https://lodash.com/) |
| **Ramda** | 工具函数 | 函数式、柯里化 | [ramdajs.com](https://ramdajs.com/) |
| **clsx** | 类名处理 | 轻量、条件类名 | [github.com/lukeed/clsx](https://github.com/lukeed/clsx) |
| **classnames** | 类名处理 | 流行、功能多 | [github.com/JedWatson/classnames](https://github.com/JedWatson/classnames) |

**推荐文章：**
- [lodash 常用函数](https://juejin.cn/post/6844904092640837645) - 防抖节流、深拷贝

---

### 样式方案

| 库 | 类型 | 特点 | 链接 |
|------|------|------|------|
| **Tailwind CSS** | 原子化 CSS | 实用优先、高效 | [tailwindcss.com](https://tailwindcss.com/) |
| **Styled Components** | CSS-in-JS | React、动态样式 | [styled-components.com](https://styled-components.com/) |
| **Emotion** | CSS-in-JS | 高性能、Source Map | [emotion.sh](https://emotion.sh/) |
| **Sass** | CSS 预处理器 | 成熟、功能全 | [sass-lang.com](https://sass-lang.com/) |
| **Less** | CSS 预处理器 | 简洁、易上手 | [lesscss.org](https://lesscss.org/) |
| **PostCSS** | CSS 工具 | 插件系统、强大 | [postcss.org](https://postcss.org/) |

**推荐文章：**
- [Tailwind CSS 实战](https://juejin.cn/post/6896924695322689549) - 快速构建 UI
- [CSS-in-JS 对比](https://juejin.cn/post/6953149562107363342) - Styled Components vs Emotion

---

### 测试

| 库 | 用途 | 特点 | 链接 |
|------|------|------|------|
| **Jest** | 单元测试 | 开箱即用、快照 | [jestjs.io](https://jestjs.io/) |
| **Vitest** | 单元测试 | Vite 原生、快速 | [vitest.dev](https://vitest.dev/) |
| **Testing Library** | 组件测试 | 用户视角、推荐 | [testing-library.com](https://testing-library.com/) |
| **Cypress** | E2E 测试 | 功能强大、易调试 | [cypress.io](https://www.cypress.io/) |
| **Playwright** | E2E 测试 | 微软出品、跨浏览器 | [playwright.dev](https://playwright.dev/) |

**推荐文章：**
- [Jest 单元测试实战](https://juejin.cn/post/6844903501789691918) - Mock、快照测试
- [Playwright E2E 测试](https://juejin.cn/post/6953149562107363342) - 自动化测试

---

### 构建优化

| 库 | 用途 | 特点 | 链接 |
|------|------|------|------|
| **webpack-bundle-analyzer** | Bundle 分析 | 可视化分析包体积 | [github.com/webpack-contrib/webpack-bundle-analyzer](https://github.com/webpack-bundle-analyzer/webpack-bundle-analyzer) |
| **babel** | 转译 | ES6+ 转 ES5 | [babeljs.io](https://babeljs.io/) |
| **esbuild** | 构建 | 超快构建 | [esbuild.github.io](https://esbuild.github.io/) |
| **SWC** | 构建 | Rust 编写、快速 | [swc.rs](https://swc.rs/) |

---

## 🎯 选型建议

### 如何选择库

1. **看下载量**: npm 周下载量 > 10 万通常比较稳定
2. **看维护**: 最近有更新、Issue 响应及时
3. **看文档**: 文档完善、示例丰富
4. **看生态**: 社区活跃、插件丰富
5. **看体积**: Bundle 体积影响加载性能

### 避免重复造轮子

| 需求 | 推荐库 | 理由 |
|------|--------|------|
| HTTP 请求 | axios | 功能全面、稳定 |
| 状态管理 | Zustand/Pinia | 简单、无样板代码 |
| 表单处理 | React Hook Form | 性能好、API 友好 |
| 日期处理 | dayjs | 轻量、API 简洁 |
| 图表 | ECharts | 功能强大、中文友好 |
| 动画 | Framer Motion | 声明式、易上手 |
| 样式 | Tailwind CSS | 开发效率高 |

---

## 📚 学习资源

| 资源 | 链接 |
|------|------|
| npm Trends | [npmtrends.com](https://www.npmtrends.com/) - 对比库的下载趋势 |
| Bundlephobia | [bundlephobia.com](https://bundlephobia.com/) - 查看库的体积 |
| JavaScript Info | [javascript.info](https://javascript.info/) - 现代 JS 教程 |
| GitHub Topics | [github.com/topics](https://github.com/topics) - 发现优质开源项目 |

---

<div align="center">

**选择合适的库，让开发更高效** 📦

[返回框架生态](./README.md) | [返回主页](../README.md)

</div>
