# 🏗️ 低代码/搭建平台精选

> 可视化搭建、表单生成器、页面配置化、Schema 驱动

**难度**: ⭐⭐⭐⭐⭐ 高级前端

---

## 📌 核心概念

### 低代码平台架构设计

- **链接**: [低代码平台架构设计](https://juejin.cn/post/6854573179354087437)
- **作者**: 架构师
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐⭐
- **阅读时间**: 约 60 分钟
- **标签**: #低代码 #架构 #可视化
- **简介**: 低代码平台整体架构设计，包括编辑器、渲染器、物料系统
- **推荐理由**: 系统化架构设计，适合从 0 到 1 搭建

### Schema 驱动开发

- **链接**: [Schema 驱动开发](https://juejin.cn/post/6896924695322689549)
- **作者**: 搭建平台开发者
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #Schema #配置化 #JSON
- **简介**: 使用 JSON Schema 描述页面结构和逻辑
- **推荐理由**: 配置化开发核心思想

---

## 🔥 经典文章

### 阿里低代码引擎解析

- **链接**: [阿里低代码引擎](https://lowcode-engine.cn/)
- **来源**: 阿里巴巴
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #低代码 #阿里 #开源
- **简介**: 阿里开源的低代码引擎架构和使用方法
- **推荐理由**: 大厂开源方案，经过生产验证

### 表单生成器设计原理

- **链接**: [表单生成器设计](https://juejin.cn/post/6953149562107363342)
- **作者**: 表单专家
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐
- **标签**: #表单 #生成器 #配置化
- **简介**: 动态表单生成器的设计思路和实现细节
- **推荐理由**: 低代码最常见场景

### 可视化编辑器实现

- **链接**: [可视化编辑器实现](https://zhuanlan.zhihu.com/p/147258369)
- **作者**: 编辑器开发者
- **来源**: 知乎
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #可视化 #编辑器 #拖拽
- **简介**: 拖拽式页面编辑器的核心实现技术
- **推荐理由**: 低代码平台核心组件

---

## 🎓 实战场景

### 营销活动页面搭建

- **链接**: [营销活动搭建平台](https://juejin.cn/post/6884404561133510664)
- **作者**: 营销平台开发者
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #营销 #活动 #搭建
- **简介**: 营销活动页面的可视化搭建平台实践
- **推荐理由**: 高频业务场景，ROI 明显

### 后台管理系统生成

- **链接**: [后台管理系统生成](https://juejin.cn/post/6844903501789691918)
- **作者**: 中台开发者
- **来源**: 掘金
- **难度**: ⭐⭐⭐⭐
- **标签**: #后台 #CRUD #生成器
- **简介**: 根据数据模型自动生成 CRUD 页面
- **推荐理由**: 减少重复劳动，提升效率

### 小程序搭建平台

- **链接**: [小程序搭建平台](https://juejin.cn/book/6857911898095689742)
- **作者**: 小程序专家
- **来源**: 掘金小册
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #小程序 #搭建 #可视化
- **简介**: 小程序页面的可视化搭建方案
- **推荐理由**: 跨端搭建场景

---

## 🛠️ 核心技术

### 拖拽实现方案

```typescript
// 拖拽核心 API
interface DragDropSystem {
  // 拖拽开始
  onDragStart(component: Component): void;
  // 拖拽中
  onDragOver(position: Position): void;
  // 拖拽结束
  onDrop(target: Container): void;
}

// 画布渲染
interface CanvasRenderer {
  // 渲染组件树
  render(tree: ComponentTree): void;
  // 更新组件
  update(componentId: string, props: Props): void;
  // 删除组件
  remove(componentId: string): void;
}
```

### Schema 设计

```json
{
  "componentName": "Page",
  "props": {
    "title": "活动页面"
  },
  "children": [
    {
      "componentName": "Button",
      "props": {
        "text": "点击我",
        "onClick": "{{actions.submit}}"
      }
    }
  ]
}
```

---

## 📊 开源项目

| 项目 | 团队 | 链接 |
|------|------|------|
| 阿里低代码引擎 | 阿里 | [lowcode-engine.cn](https://lowcode-engine.cn/) |
| Amis | 百度 | [aisuda.bce.baidu.com](https://aisuda.bce.baidu.com/) |
| Formily | 阿里 | [formilyjs.org](https://formilyjs.org/) |
| Variant Form | 开源 | [vform666.com](https://vform666.com/) |
| 氚云 | 简道云 | [h3yun.com](https://www.h3yun.com/) |

---

## 📚 学习资源

| 资源 | 链接 | 难度 |
|------|------|------|
| 低代码引擎文档 | [lowcode-engine.cn](https://lowcode-engine.cn/) | ⭐⭐⭐⭐ |
| Formily 文档 | [formilyjs.org](https://formilyjs.org/) | ⭐⭐⭐⭐⭐ |
| Amis 文档 | [aisuda.bce.baidu.com](https://aisuda.bce.baidu.com/) | ⭐⭐⭐⭐ |

---

<div align="center">

**低代码，让开发更高效** 🏗️

[返回主页](../README.md)

</div>
