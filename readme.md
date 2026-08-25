# JSON Lens 🔍

> 在线 JSON 格式化、校验、树形视图工具 —— **数据全程本地处理，不上传服务器**

🔗 **在线使用：<https://jsonlens.cn/>**

## ✨ 特性

- 🔒 **本地运行**：所有解析、格式化、校验都在浏览器本地完成，数据绝不上传服务器，粘贴生产环境数据也放心（可断网使用）
- 🌳 **树形视图**：层级结构一目了然，支持逐级展开/折叠，几万行的大文件也不卡（懒渲染，折叠的节点不真正渲染）
- 📊 **表格视图**：对象数组一键转表格，嵌套字段自动扁平化（`addr.city` 自动变成一列），横向对比字段值超直观
- ⚡ **格式化 / 压缩 / 校验**：一键美化、压成一行、错误精确定位到行和列
- 🎨 **语法高亮**：键名、字符串、数字、布尔值、null 用不同颜色区分
- 📖 **免费中文教程**：18 篇 JSON 入门与避坑教程，从零讲起

## 🚀 快速使用

打开 [jsonlens.cn](https://jsonlens.cn/) → 粘贴 JSON 或拖入 `.json` 文件 → 立即解析。无需安装、无需注册、无需登录。

## 🔐 隐私说明

JSON Lens 是**纯前端工具**，所有数据仅在浏览器本地内存中解析和展示，**不会发送到任何服务器**。可以放心粘贴生产环境、日志、配置文件中的敏感数据。断网也能用。

## 📚 JSON 教程精选

- [JSON 常见错误大全：尾逗号、单引号、注释](https://jsonlens.cn/guide/json-common-errors)
- [JSON.parse 报错原因汇总](https://jsonlens.cn/guide/json-parse-error)
- [JSON 错误如何定位到行和列](https://jsonlens.cn/guide/json-error-locate)
- [JSON 数据类型详解：6 种类型一次搞懂](https://jsonlens.cn/guide/json-data-types)
- [JSON 嵌套数据如何快速看懂](https://jsonlens.cn/guide/json-nested-reading)
- [JSON 大文件处理技巧：几万行不卡死](https://jsonlens.cn/guide/json-large-file)

完整 18 篇教程见 [jsonlens.cn 指南区](https://jsonlens.cn/)。

## 🛠 技术栈

| 部分   | 技术                       |
| ---- | ------------------------ |
| 前端工具 | 原生 JavaScript（零依赖、零构建）   |
| 站点   | Astro + MDX（静态生成，SEO 友好） |
| 部署   | Netlify                  |

## 🤝 反馈

工具使用中有任何问题、建议，欢迎在 [GitHub Issues](https://github.com/hongfei1993/jsonlens/issues) 提 issue，每条都会看，工具会持续迭代。

---

© 2026 JSON Lens · [jsonlens.cn](https://jsonlens.cn/)
