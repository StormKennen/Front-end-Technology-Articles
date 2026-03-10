# 🔒 Web 安全与防护精选

> 数据安全、JS 逆向防护、XSS/CSRF 防御、认证授权

**难度**: ⭐⭐⭐⭐⭐ 高级前端

---

## 📌 核心安全标准

### OWASP Top 10 2025

- **链接**: [OWASP Top 10 2025](https://owasp.org/Top10/2025/)
- **来源**: OWASP Foundation
- **难度**: ⭐⭐⭐⭐⭐
- **阅读时间**: 约 60 分钟
- **标签**: #安全 #OWASP #Web 安全 #标准
- **简介**: 全球公认的 Web 应用十大安全风险标准，2025 最新版本。涵盖注入攻击、认证失效、敏感数据泄露等核心风险
- **推荐理由**: 安全开发必读标准，面试高频考点

### Web Security Academy

- **链接**: [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- **来源**: PortSwigger (Burp Suite 团队)
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #安全 #实战 #渗透测试 #XSS #SQL 注入
- **简介**: 免费的 Web 安全在线培训平台，包含交互式实验和漏洞练习
- **推荐理由**: 理论与实践结合，提供真实漏洞环境练习

---

## 🔐 认证与授权

### OAuth 2.0 与 OIDC 完全指南

- **链接**: [OAuth 2.0 Simplified](https://aaronparecki.com/oauth-2-simplified/)
- **作者**: Aaron Parecki
- **来源**: OAuth.com
- **难度**: ⭐⭐⭐⭐
- **阅读时间**: 约 30 分钟
- **标签**: #OAuth #认证 #授权 #安全
- **简介**: OAuth 2.0 授权流程的清晰讲解，避免常见安全陷阱
- **推荐理由**: OAuth 领域权威作者，内容准确易懂

### JWT 安全最佳实践

- **链接**: [JWT Best Practices](https://auth0.com/blog/jwt-security-best-practices/)
- **来源**: Auth0 Blog
- **难度**: ⭐⭐⭐⭐
- **阅读时间**: 约 25 分钟
- **标签**: #JWT #Token #认证 #安全
- **简介**: JWT 使用中的安全注意事项，包括签名算法、过期时间、存储方式等
- **推荐理由**: Auth0 团队出品，生产环境经验总结

### 会话管理安全

- **链接**: [Session Management Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html)
- **来源**: OWASP
- **难度**: ⭐⭐⭐⭐
- **标签**: #会话 #Cookie #安全 #认证
- **简介**: 会话管理的完整安全指南，包括 Cookie 属性、令牌生成、过期策略
- **推荐理由**: OWASP 官方速查表，实践指导性强

---

## 🛡️ XSS 防护

### Content Security Policy (CSP) 完全指南

- **链接**: [CSP Guide](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/CSP)
- **来源**: MDN
- **难度**: ⭐⭐⭐⭐
- **阅读时间**: 约 40 分钟
- **标签**: #CSP #XSS #安全 #HTTP
- **简介**: CSP 策略配置详解，有效防止 XSS 攻击
- **推荐理由**: MDN 官方文档，权威准确

### XSS 攻击与防御实战

- **链接**: [XSS Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html)
- **来源**: OWASP
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #XSS #攻击 #防御 #安全
- **简介**: XSS 攻击向量汇总和防御措施，包含各种绕过技巧
- **推荐理由**: 攻防兼备，了解攻击才能更好防御

### DOM-based XSS 防护

- **链接**: [DOM-based XSS Prevention](https://cheatsheetseries.owasp.org/cheatsheets/DOM_based_XSS_Prevention_Cheat_Sheet.html)
- **来源**: OWASP
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #XSS #DOM #前端安全
- **简介**: 针对 DOM 型 XSS 的专项防护指南，前端开发必备
- **推荐理由**: 专注于前端 DOM 操作安全，实用性强

---

## 🔒 数据安全防护

### 前端敏感数据保护

- **链接**: [Client-Side Data Security](https://cheatsheetseries.owasp.org/cheatsheets/Client-side_Storage_Cheat_Sheet.html)
- **来源**: OWASP
- **难度**: ⭐⭐⭐⭐
- **标签**: #数据安全 #LocalStorage #加密
- **简介**: 客户端数据存储安全指南，包括 LocalStorage、IndexedDB 的安全使用
- **推荐理由**: 明确前端数据存储的安全边界和最佳实践

### HTTPS 与传输安全

- **链接**: [Transport Layer Protection](https://cheatsheetseries.owasp.org/cheatsheets/Transport_Layer_Protection_Cheat_Sheet.html)
- **来源**: OWASP
- **难度**: ⭐⭐⭐
- **标签**: #HTTPS #TLS #传输安全
- **简介**: 传输层安全防护，包括 TLS 配置、证书验证、HSTS 等
- **推荐理由**: 保障数据传输安全的基础知识

### 密码存储与哈希

- **链接**: [Password Storage Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)
- **来源**: OWASP
- **难度**: ⭐⭐⭐⭐
- **标签**: #密码 #哈希 #bcrypt #安全
- **简介**: 密码存储的安全实践，包括哈希算法选择、盐值生成等
- **推荐理由**: 密码安全是系统安全的基石

---

## 🚫 JS 逆向防护

### JavaScript 代码混淆与保护

- **链接**: [JavaScript Obfuscation Techniques](https://www.javascriptobfuscator.com/)
- **来源**: JavaScript Obfuscator
- **难度**: ⭐⭐⭐⭐
- **标签**: #混淆 #代码保护 #逆向
- **简介**: JavaScript 代码混淆技术介绍，增加逆向工程难度
- **推荐理由**: 了解混淆技术，评估保护效果

### 反调试与反爬技术

- **链接**: [Anti-Debugging Techniques](https://www.imperva.com/learn/application-security/)
- **来源**: Imperva
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #反调试 #逆向 #安全
- **简介**: 前端反调试技术和反爬虫策略，保护业务逻辑
- **推荐理由**: 实战性强，了解攻防对抗思路

### WebAssembly 代码保护

- **链接**: [WebAssembly Security](https://developer.mozilla.org/zh-CN/docs/WebAssembly/Security)
- **来源**: MDN
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #WebAssembly #安全 #代码保护
- **简介**: 使用 WebAssembly 保护核心算法，增加逆向难度
- **推荐理由**: 前沿技术方案，适合核心业务逻辑保护

---

## 🔍 安全审计与测试

### 前端安全审计清单

- **链接**: [Frontend Security Checklist](https://github.com/ziadoz/awesome-javascript#security)
- **来源**: GitHub Awesome JS
- **难度**: ⭐⭐⭐⭐
- **标签**: #安全审计 #清单 #最佳实践
- **简介**: 前端项目安全检查清单，覆盖常见安全问题
- **推荐理由**: 系统化的安全检查流程

### 自动化安全测试

- **链接**: [Security Testing Tools](https://owasp.org/www-project-top-ten/#tools)
- **来源**: OWASP
- **难度**: ⭐⭐⭐⭐
- **标签**: #安全测试 #自动化 #工具
- **简介**: Web 安全测试工具汇总，包括 Burp Suite、OWASP ZAP 等
- **推荐理由**: 工具链完善，提升测试效率

---

## 📚 进阶阅读

### Web Application Hacker's Handbook

- **链接**: [The Web Application Hacker's Handbook](https://www.wiley.com/en-us/The+Web+Application+Hacker%27s+Handbook%3A+Finding+and+Exploiting+Security+Flaws%2C+2nd+Edition-p-9781118026472)
- **作者**: Dafydd Stuttard, Marcus Pinto
- **难度**: ⭐⭐⭐⭐⭐
- **标签**: #书籍 #安全 #渗透测试
- **简介**: Web 安全领域的经典著作，深入讲解攻击与防御技术
- **推荐理由**: 安全从业者必读书籍

### Google Security Blog

- **链接**: [Google Security Blog](https://security.googleblog.com/)
- **来源**: Google
- **难度**: ⭐⭐⭐⭐
- **标签**: #安全 #博客 #前沿
- **简介**: Google 安全团队官方博客，分享最新安全研究和实践
- **推荐理由**: 了解行业前沿安全动态

---

## 🛠️ 安全工具

| 工具 | 用途 | 链接 |
|------|------|------|
| Burp Suite | 渗透测试 | [portswigger.net](https://portswigger.net/burp) |
| OWASP ZAP | 安全扫描 | [zaproxy.org](https://www.zaproxy.org/) |
| CSP Evaluator | CSP 检查 | [csp-evaluator.withgoogle.com](https://csp-evaluator.withgoogle.com/) |
| Security Headers | 头信息检查 | [securityheaders.com](https://securityheaders.com/) |
| SSL Labs | SSL 测试 | [ssllabs.com](https://www.ssllabs.com/ssltest/) |

---

## 🎯 学习路径建议

```
初级 (1-2 个月)
├─ HTTPS/TLS 基础
├─ Cookie 安全属性
├─ XSS 基础与防御
└─ 输入验证

中级 (3-6 个月)
├─ OAuth 2.0 / OIDC
├─ JWT 安全
├─ CSP 配置
└─ 会话管理

高级 (6-12 个月)
├─ OWASP Top 10 深入
├─ 代码混淆与保护
├─ 反调试技术
└─ 自动化安全测试
```

---

<div align="center">

**安全无小事，防护从细节做起** 🔒

[返回主页](../README.md) | [返回安全分类](../security/README.md)

</div>
