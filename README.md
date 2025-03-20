# SolidColor.github.io

🎨 一个简洁优雅的纯色背景生成网站，为设计师、演讲者和壁纸爱好者提供高质量的纯色背景。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## ✨ 特性

- 🌈 支持中文、日文、英文三种语言界面
- 🎯 快速生成任意纯色背景
- 📱 完全响应式设计，支持各种设备
- 🔧 可自定义颜色参数（RGB/HEX/HSL）
- TODO: 💾 一键下载生成的背景图片
- TODO: 🌓 支持亮色/暗色主题切换

## 🛠️ 技术栈

- **框架**：[Next.js](https://nextjs.org/) - React 框架，提供服务端渲染和静态生成
- **语言**：[TypeScript](https://www.typescriptlang.org/) - 提供类型安全的 JavaScript 开发体验
- **样式**：[Tailwind CSS](https://tailwindcss.com/) - 实用优先的 CSS 框架
- **代码质量**：
  - [ESLint](https://eslint.org/) - 代码质量检查
  - [Prettier](https://prettier.io/) - 代码格式化工具

## 🚀 快速开始

1. **克隆项目**
```bash
git clone https://github.com/SolidColor/SolidColor.github.io.git
cd SolidColor.github.io
```

2. **安装依赖**
```bash
npm install
# 或者使用 yarn
yarn install
```

3. **启动开发服务器**
```bash
npm run dev
# 或者使用 yarn
yarn dev
```

4. **访问网站**
打开浏览器访问 http://localhost:3000

## 📂 项目结构

```
SolidColor.github.io/
├── app/                # Next.js 应用目录
│   ├── layout.tsx     # 根布局组件
│   ├── page.tsx       # 首页组件
│   └── [...lang]/     # 国际化路由
├── components/        # 可复用组件
├── public/           # 静态资源
├── styles/          # 全局样式
└── types/           # TypeScript 类型定义
```

## 🤝 贡献指南

我们欢迎所有形式的贡献，无论是新功能、bug 修复还是文档改进！

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 📝 许可证

本项目采用 MIT 许可证 - 详情请参见 [LICENSE](LICENSE) 文件

## 🔗 相关链接

- 在线预览：[https://solidcolor.github.io](https://solidcolor.github.io)
- 项目仓库：[https://github.com/SolidColor/SolidColor.github.io](https://github.com/SolidColor/SolidColor.github.io)
- 问题反馈：[Issues](https://github.com/SolidColor/SolidColor.github.io/issues)