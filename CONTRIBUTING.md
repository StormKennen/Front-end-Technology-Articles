# 🤝 贡献指南

感谢你对本仓库的兴趣！欢迎一起完善前端技术文章大全。

---

## 📝 如何贡献

### 1. 添加新文章

#### 找到对应分类

根据文章主题，找到对应的分类文件：
- `fundamentals/html.md` - HTML 相关
- `fundamentals/css.md` - CSS 相关
- `fundamentals/javascript.md` - JavaScript 相关
- `frameworks/react.md` - React 相关
- `frameworks/vue.md` - Vue 相关
- `engineering/` - 工程化相关
- `performance/` - 性能优化相关
- `advanced/` - 进阶主题

#### 文章格式

```markdown
### 文章标题

- **链接**: [文章标题](https://example.com/article)
- **作者**: 作者名/团队
- **来源**: 网站/博客名称
- **发布日期**: 2026-03-10
- **难度**: ⭐⭐⭐ (1-5 星)
- **阅读时间**: 约 10 分钟
- **标签**: #CSS #布局 #教程
- **简介**: 用 1-2 句话简要描述文章内容和价值
- **推荐理由**: (可选) 为什么推荐这篇文章
```

#### 示例

```markdown
### Popover API or Dialog API: Which to Choose?

- **链接**: [Popover API or Dialog API](https://css-tricks.com/popover-api-or-dialog-api-which-to-choose/)
- **作者**: Adrian Roselli
- **来源**: CSS-Tricks
- **发布日期**: 2026-02-20
- **难度**: ⭐⭐⭐
- **阅读时间**: 约 15 分钟
- **标签**: #CSS #API #无障碍 #HTML
- **简介**: 深入对比 Popover API 和 Dialog API 的区别，帮助开发者在合适场景选择正确的 API
- **推荐理由**: 内容详实，包含无障碍访问的最佳实践
```

---

### 2. 创建新分类

如果现有分类无法容纳某篇文章，可以：

1. 在对应目录下创建新文件
2. 在 `README.md` 中添加分类链接
3. 提交 PR 时说明理由

---

### 3. 更新资源列表

在 `resources/` 目录下维护各类资源：

- `official-docs.md` - 官方文档链接
- `blogs.md` - 技术博客/媒体
- `communities.md` - 技术社区/论坛
- `tools.md` - 开发工具
- `courses.md` - 在线课程

---

## ✅ 质量标准

### 文章要求

- [ ] 内容质量高，有实质性技术内容
- [ ] 来源可靠（官方文档、知名博客、技术社区等）
- [ ] 信息准确，无明显错误
- [ ] 时效性较好（优先近 2 年内容，经典文章除外）
- [ ] 中文或英文均可

### 不接收的内容

- ❌ 营销号/标题党文章
- ❌ 内容空洞、拼字数的文章
- ❌ 已过时且无参考价值的内容
- ❌ 抄袭/搬运内容
- ❌ 需要付费才能阅读的文章（除非特别说明）

---

## 🔄 提交流程

### 1. Fork 仓库

```bash
# 在 GitHub 上点击 Fork 按钮
```

### 2. 克隆到本地

```bash
git clone https://github.com/YOUR_USERNAME/Front-end-Technology-Articles.git
cd Front-end-Technology-Articles
```

### 3. 创建分支

```bash
git checkout -b add/article-xxx
```

### 4. 编辑文件

按照格式添加文章内容

### 5. 提交更改

```bash
git add .
git commit -m "docs: 添加 CSS 布局相关文章 3 篇"
```

### 6. 推送并创建 PR

```bash
git push origin add/article-xxx
```

然后在 GitHub 上创建 Pull Request

---

## 📋 Commit 规范

参考 [Conventional Commits](https://www.conventionalcommits.org/)

### 类型

- `docs:` 文档更新（文章、资源）
- `feat:` 新增功能/分类
- `fix:` 修复错误链接/信息
- `refactor:` 重构文件结构
- `chore:` 其他杂项

### 示例

```bash
git commit -m "docs: 添加 React Hooks 最佳实践文章"
git commit -m "fix: 修复 CSS-Tricks 链接失效问题"
git commit -m "feat: 新增 Web Components 分类"
```

---

## 🏷️ 标签规范

使用统一的标签格式，方便检索：

### 技术栈
`#HTML` `#CSS` `#JavaScript` `#TypeScript` `#React` `#Vue` `#Angular` `#Svelte`

### 主题
`#布局` `#动画` `#性能` `#安全` `#无障碍` `#SEO` `#测试` `#调试`

### 内容类型
`#教程` `#指南` `#最佳实践` `#案例分析` `#技术分享` `#源码解析`

---

## ❓ 常见问题

### Q: 可以添加自己的博客文章吗？

A: 可以！只要内容质量高、有技术价值，欢迎添加。但请确保：
- 不是纯营销内容
- 有实质性技术分享
- 同一作者不要过度集中

### Q: 文章有字数要求吗？

A: 没有硬性要求，但建议：
- 教程类：1500 字以上
- 技巧类：500 字以上
- 源码解析：2000 字以上

### Q: 如何处理失效链接？

A: 发现失效链接请：
1. 尝试查找文章的新地址
2. 如果找不到，提交 PR 移除或标注"已失效"
3. 使用 `git commit -m "fix: 移除失效链接"`

---

## 🙏 感谢

感谢每一位贡献者！你的分享将帮助更多开发者成长。

---

<div align="center">

**一起建设更好的前端学习资源库！** 🚀

</div>
