# ⚛️ 框架生态

> React、Vue、以及解决具体问题的成熟库

---

## 📚 文章列表

| 文章 | 难度 | 主题 |
|------|------|------|
| [React](./react.md) | ⭐⭐⭐⭐ | Hooks、生态、最佳实践 |
| [Vue](./vue.md) | ⭐⭐⭐⭐ | Vue 3、Composition API、生态库 |
| [常用库](./libraries.md) | ⭐⭐⭐⭐ | HTTP、状态管理、表单、UI 组件等 |

---

## 🔥 核心框架

### React

**涵盖主题：**
- React Hooks 完全指南
- useEffect 深度解析
- React Server Components
- 性能优化 (memo、useMemo)
- 状态管理 (Redux、Zustand)
- 路由 (React Router)

**适合人群：** 中高级前端开发者

**官方文档：** [react.dev](https://react.dev/)

---

### Vue

**涵盖主题：**
- Vue 3 Composition API
- 响应式原理 (Proxy)
- Vue Router 4
- Pinia 状态管理
- Nuxt 3 服务端渲染
- 自定义 Composable

**适合人群：** 中高级前端开发者

**官方文档：** [cn.vuejs.org](https://cn.vuejs.org/)

---

## 📦 常用库分类

### 数据请求

| 库 | 框架 | 用途 |
|------|------|------|
| axios | 通用 | HTTP 客户端 |
| react-query | React | 服务端状态管理 |
| swr | React | 数据请求 Hooks |
| ky | 通用 | 轻量 Fetch 封装 |

---

### 状态管理

| 库 | 框架 | 特点 |
|------|------|------|
| Redux Toolkit | React | 官方推荐 |
| Zustand | React | 轻量简单 |
| Jotai | React | 原子化状态 |
| Pinia | Vue | 官方推荐 |
| MobX | 通用 | 响应式 |

---

### 表单处理

| 库 | 框架 | 特点 |
|------|------|------|
| React Hook Form | React | 性能好 |
| Formik | React | 功能全面 |
| VeeValidate | Vue | 验证强大 |
| Formily | 通用 | 复杂表单 |

---

### UI 组件库

#### React
- **Ant Design** - 企业级
- **Material-UI** - Material Design
- **Chakra UI** - 易用
- **Headless UI** - 无样式

#### Vue
- **Element Plus** - 企业级
- **Ant Design Vue** - Ant Design
- **Naive UI** - TypeScript 支持好
- **Vant** - 移动端

---

### 图表可视化

| 库 | 特点 |
|------|------|
| ECharts | 功能强大、中文友好 |
| AntV | 阿里出品、系列全 |
| Chart.js | 简单轻量 |
| Recharts | React 友好 |
| D3.js | 强大灵活 |

---

### 动画

| 库 | 框架 | 特点 |
|------|------|------|
| Framer Motion | React | 声明式 |
| GSAP | 通用 | 专业级 |
| Anime.js | 通用 | 轻量 |
| Lottie | 通用 | AE 导出 |

---

### 日期时间

| 库 | 特点 |
|------|------|
| dayjs | 轻量、API 友好 |
| date-fns | 函数式、Tree-shaking |
| Luxon | Moment 作者新作 |

---

### 样式方案

| 库 | 类型 |
|------|------|
| Tailwind CSS | 原子化 CSS |
| Styled Components | CSS-in-JS |
| Emotion | CSS-in-JS |
| Sass | 预处理器 |
| Less | 预处理器 |

---

### 测试

| 库 | 用途 |
|------|------|
| Jest | 单元测试 |
| Vitest | 单元测试 (Vite) |
| Testing Library | 组件测试 |
| Cypress | E2E 测试 |
| Playwright | E2E 测试 |

---

## 🎯 选型建议

### 如何选择库

1. **看下载量**: npm 周下载量 > 10 万
2. **看维护**: 最近有更新、Issue 响应及时
3. **看文档**: 文档完善、示例丰富
4. **看生态**: 社区活跃、插件丰富
5. **看体积**: Bundle 体积影响性能

### 推荐组合

#### React 技术栈
```
React + TypeScript
├─ 状态管理：Zustand / Redux Toolkit
├─ 数据请求：react-query + axios
├─ 路由：React Router
├─ 表单：React Hook Form
├─ UI：Ant Design / Chakra UI
├─ 样式：Tailwind CSS
└─ 测试：Jest + Testing Library
```

#### Vue 技术栈
```
Vue 3 + TypeScript
├─ 状态管理：Pinia
├─ 数据请求：axios
├─ 路由：Vue Router
├─ 表单：VeeValidate
├─ UI：Element Plus / Naive UI
├─ 样式：Sass / Tailwind CSS
└─ 测试：Vitest + Testing Library
```

---

## 📖 学习资源

| 资源 | 链接 |
|------|------|
| React 官方 | [react.dev](https://react.dev/) |
| Vue 官方 | [cn.vuejs.org](https://cn.vuejs.org/) |
| npm Trends | [npmtrends.com](https://www.npmtrends.com/) |
| Bundlephobia | [bundlephobia.com](https://bundlephobia.com/) |

---

[返回主页](../README.md)
