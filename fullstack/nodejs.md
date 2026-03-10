# 🟢 Node.js 全栈开发精选

> 服务端开发、BFF 层、API 设计、全栈架构

**难度**: ⭐⭐⭐⭐⭐ 高级前端

---

## 📌 核心概念

### Node.js 官方文档

- **链接**: [Node.js 文档](https://nodejs.org/zh-cn/docs/)
- **来源**: Node.js 官方
- **难度**: ⭐⭐⭐⭐
- **阅读时间**: 约 40 分钟
- **标签**: #NodeJS #基础 #文档
- **简介**: Node.js API 文档和使用指南
- **推荐理由**: 官方文档，权威准确

### BFF 架构设计

- **链接**: [BFF 架构设计](https://juejin.cn/post/6844903501789691918)
- **作者**: 架构师
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #BFF #架构 #后端
- **简介**: Backend for Frontend 架构设计和实践
- **推荐理由**: 前端向后延伸的架构模式

---

## 🔥 经典文章

### Express 框架最佳实践

- **链接**: [Express 最佳实践](https://juejin.cn/post/6854573179354087437)
- **作者**: Node.js 专家
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐
- **标签**: #Express #框架 #最佳实践
- **简介**: Express 路由、中间件、错误处理最佳实践
- **推荐理由**: 经典框架，使用广泛

### Koa2 源码解析

- **链接**: [Koa2 源码解析](https://juejin.cn/post/6884404561133510664)
- **作者**: 框架研究者
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #Koa #源码 #中间件
- **简介**: Koa2 洋葱模型、中间件机制源码分析
- **推荐理由**: 深入理解 Node.js 框架设计

### NestJS 企业级开发

- **链接**: [NestJS 企业级开发](https://juejin.cn/post/6953149562107363342)
- **作者**: 企业级开发者
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #NestJS #企业级 #TypeScript
- **简介**: 使用 NestJS 构建企业级 Node.js 应用
- **推荐理由**: 类 Angular 架构，适合大型项目

---

## 🎓 实战场景

### RESTful API 设计

- **链接**: [RESTful API 设计](https://zhuanlan.zhihu.com/p/138693907)
- **作者**: API 设计师
- **来源**: 知乎
- **难度**: ⭐⭐⭐⭐
- **标签**: #API #RESTful #设计
- **简介**: RESTful API 设计规范和实践
- **推荐理由**: API 设计基础

### JWT 认证实现

- **链接**: [JWT 认证实现](https://juejin.cn/post/6896924695322689549)
- **作者**: 安全开发者
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐
- **标签**: #JWT #认证 #安全
- **简介**: Node.js 实现 JWT 认证完整流程
- **推荐理由**: 用户认证必备技能

### 数据库操作 (MongoDB)

- **链接**: [MongoDB 操作](https://juejin.cn/post/6961714845313024036)
- **作者**: 数据库专家
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐
- **标签**: #MongoDB #数据库 #Mongoose
- **简介**: 使用 Mongoose 操作 MongoDB 数据库
- **推荐理由**: NoSQL 数据库常用方案

### 数据库操作 (MySQL)

- **链接**: [MySQL 操作](https://juejin.cn/post/6844904092640837645)
- **作者**: 数据库开发者
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐
- **标签**: #MySQL #数据库 #Sequelize
- **简介**: 使用 Sequelize ORM 操作 MySQL
- **推荐理由**: 关系型数据库常用方案

---

## 🛠️ 技术栈

### Web 框架

| 框架 | 特点 | 链接 |
|------|------|------|
| Express | 轻量灵活 | [expressjs.com](https://expressjs.com/) |
| Koa | 洋葱模型 | [koajs.com](https://koajs.com/) |
| NestJS | 企业级 | [nestjs.com](https://nestjs.com/) |
| Fastify | 高性能 | [fastify.io](https://www.fastify.io/) |

### 数据库 ORM

| ORM | 数据库 | 链接 |
|-----|--------|------|
| Mongoose | MongoDB | [mongoosejs.com](https://mongoosejs.com/) |
| Sequelize | MySQL/PG | [sequelize.org](https://sequelize.org/) |
| Prisma | 多数据库 | [prisma.io](https://www.prisma.io/) |
| TypeORM | TypeScript | [typeorm.io](https://typeorm.io/) |

### 认证授权

| 库 | 用途 | 链接 |
|----|------|------|
| jsonwebtoken | JWT | [github.com/auth0/node-jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) |
| passport | 认证中间件 | [passportjs.org](https://www.passportjs.org/) |
| bcrypt | 密码加密 | [github.com/kelektiv/node.bcrypt.js](https://github.com/kelektiv/node.bcrypt.js) |

---

## 📊 全栈架构模式

```
┌─────────────────────────────────────┐
│           前端 (React/Vue)          │
└──────────────┬──────────────────────┘
               │ HTTP/GraphQL
┌──────────────▼──────────────────────┐
│         BFF 层 (Node.js)            │
│  - API 聚合  - 数据转换  - 认证授权   │
└──────────────┬──────────────────────┘
               │
    ┌──────────┼──────────┐
    │          │          │
┌───▼───┐ ┌───▼───┐ ┌───▼───┐
│ MySQL │ │MongoDB│ │ Redis │
└───────┘ └───────┘ └───────┘
```

---

## 📚 学习资源

| 资源 | 链接 | 难度 |
|------|------|------|
| Node.js 官方文档 | [nodejs.org](https://nodejs.org/) | ⭐⭐⭐⭐ |
| Express 指南 | [expressjs.com](https://expressjs.com/) | ⭐⭐⭐ |
| NestJS 文档 | [docs.nestjs.com](https://docs.nestjs.com/) | ⭐⭐⭐⭐⭐ |
| Node.js 设计模式 | [github.com/davidg-perez](https://github.com/davidg-perez/nodejs-design-patterns) | ⭐⭐⭐⭐⭐ |

---

<div align="center">

**Node.js，前端向后端的自然延伸** 🟢

[返回主页](../README.md)

</div>
