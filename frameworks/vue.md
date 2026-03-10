# 🟢 Vue 技术文章精选

> Vue 3、Composition API、生态库、最佳实践

**难度**: ⭐⭐⭐⭐ 中高级前端

---

## 📌 核心概念

### Vue 3 官方文档

- **链接**: [Vue 3 文档](https://cn.vuejs.org/)
- **来源**: Vue.js 官方
- **难度**: ⭐⭐⭐⭐
- **阅读时间**: 约 60 分钟
- **标签**: #Vue3 #官方文档 #CompositionAPI
- **简介**: Vue 3 完整 API 参考和指南，包含 Composition API
- **推荐理由**: 官方文档，权威准确，中文友好

### Vue 2 到 Vue 3 迁移指南

- **链接**: [Vue 3 迁移指南](https://v3-migration.vuejs.org/zh/)
- **来源**: Vue.js 官方
- **难度**: ⭐⭐⭐⭐
- **标签**: #Vue3 #迁移 #升级
- **简介**: Vue 2 项目升级到 Vue 3 的完整指南和破坏性变更
- **推荐理由**: 升级必备，避免踩坑

---

## 🔥 经典文章

### Vue3 Composition API 完全指南

- **链接**: [Composition API 完全指南](https://juejin.cn/post/6990841927313817636)
- **作者**: Vue 技术探索者
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #Vue3 #CompositionAPI #响应式
- **简介**: Composition API 深入讲解，包括 setup、ref、reactive、computed 等
- **推荐理由**: 中文社区高赞文章，系统讲解

### Vue3 响应式原理

- **链接**: [Vue3 响应式原理](https://juejin.cn/post/6884404561133510664)
- **作者**: Vue 源码研究者
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #Vue3 #Proxy #源码解析
- **简介**: Proxy 实现响应式的完整流程，对比 Vue2 的 Object.defineProperty
- **推荐理由**: 深入理解 Vue3 核心机制

### Vue Router 4 实战

- **链接**: [Vue Router 4 实战](https://juejin.cn/post/6953149562107363342)
- **作者**: 路由专家
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐
- **标签**: #VueRouter #路由 #SPA
- **简介**: Vue Router 4 配置、导航守卫、路由懒加载等实战技巧
- **推荐理由**: 路由管理必备技能

### Pinia 状态管理

- **链接**: [Pinia 状态管理](https://juejin.cn/post/6896924695322689549)
- **作者**: 状态管理专家
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐
- **标签**: #Pinia #状态管理 #Vuex
- **简介**: Pinia 官方推荐的 Vue 状态管理库，比 Vuex 更简洁
- **推荐理由**: Vue 3 官方推荐，替代 Vuex

---

## 🎓 实战场景

### 组件通信方案

- **链接**: [Vue 组件通信方案](https://zhuanlan.zhihu.com/p/138693907)
- **作者**: Vue 开发者
- **来源**: 知乎
- **难度**: ⭐⭐⭐⭐
- **标签**: #Vue #组件通信 #Props
- **简介**: props/emit、provide/inject、Vuex/Pinia 等通信方案对比
- **推荐理由**: 组件设计基础

### 自定义 Composable

- **链接**: [自定义 Composable](https://juejin.cn/post/6961714845313024036)
- **作者**: Composition API 实践者
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #Vue3 #Composable #逻辑复用
- **简介**: 使用 Composition API 封装可复用逻辑
- **推荐理由**: 代码复用的最佳实践

### 服务端渲染 (Nuxt 3)

- **链接**: [Nuxt 3 实战](https://nuxt.com/docs/getting-started/introduction)
- **来源**: Nuxt 官方
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #Nuxt3 #SSR #服务端渲染
- **简介**: Nuxt 3 框架使用，实现 SSR、SSG 等高级功能
- **推荐理由**: Vue 生态的 Next.js

---

## 🛠️ 生态库推荐

### 状态管理

| 库 | 用途 | 链接 |
|------|------|------|
| Pinia | 官方推荐状态管理 | [pinia.vuejs.org](https://pinia.vuejs.org/) |
| Vuex | Vue 2 经典状态管理 | [vuex.vuejs.org](https://vuex.vuejs.org/) |

### 路由

| 库 | 用途 | 链接 |
|------|------|------|
| Vue Router | 官方路由 | [router.vuejs.org](https://router.vuejs.org/zh/) |

### UI 组件库

| 库 | 特点 | 链接 |
|------|------|------|
| Element Plus | Element UI 的 Vue3 版 | [element-plus.org](https://element-plus.org/) |
| Ant Design Vue | Ant Design 的 Vue 实现 | [antdv.com](https://antdv.com/) |
| Naive UI | 完整 TypeScript 支持 | [naiveui.com](https://www.naiveui.com/) |
| Vant | 移动端组件库 | [vant-ui.github.io](https://vant-ui.github.io/vant/) |

### 工具库

| 库 | 用途 | 链接 |
|------|------|------|
| VueUse | Composition API 工具集 | [vueuse.org](https://vueuse.org/) |
| @vueuse/core | 常用 Composable 集合 | [vueuse.org](https://vueuse.org/) |
| axios | HTTP 请求库 | [axios-http.com](https://axios-http.com/) |
| dayjs | 日期处理 | [day.js.org](https://day.js.org/) |

---

## 📊 Vue vs React 对比

| 特性 | Vue | React |
|------|-----|-------|
| 响应式 | 自动 (Proxy) | 手动 (useState) |
| 模板 | 模板语法 | JSX |
| 状态管理 | Pinia/Vuex | Redux/Zustand |
| 路由 | Vue Router | React Router |
| 学习曲线 | 平缓 | 陡峭 |
| 灵活性 | 约定优于配置 | 配置优于约定 |

---

## 📚 学习资源

| 资源 | 链接 | 难度 |
|------|------|------|
| Vue 3 官方文档 | [cn.vuejs.org](https://cn.vuejs.org/) | ⭐⭐⭐⭐ |
| Vue 技术揭秘 | [github.com/hooyue/vue-analysis](https://github.com/hooyue/vue-analysis) | ⭐⭐⭐⭐⭐ |
| Vue Mastery | [vue-mastery.com](https://www.vue-mastery.com/) | ⭐⭐⭐⭐ |
| Vue School | [vueschool.io](https://vueschool.io/) | ⭐⭐⭐⭐ |

---

<div align="center">

**Vue.js，渐进式前端框架** 🟢

[返回框架生态](../README.md) | [返回主页](../../README.md)

</div>
