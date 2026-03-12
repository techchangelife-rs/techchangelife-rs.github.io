# TechChangeLife

探索 AI、编程与教育的无限可能。

这是一个基于 [VitePress](https://vitepress.dev/) 构建的个人博客与知识库，记录技术成长，分享生活点滴。

## ✨ 特性

- 📚 **技术专栏**：涵盖前端、后端、AI、算法等多个领域
- 🧮 **数学与教育**：奥数思维、数学原理可视化
- 🏸 **生活与健康**：羽毛球技术、中医养生
- 📊 **丰富图表**：集成 Mermaid 流程图与 KaTeX 数学公式
- 🎨 **精美主题**：定制化 VitePress 主题，支持标签云、时间轴等

## 🛠️ 技术栈

- **框架**: [VitePress](https://vitepress.dev/)
- **UI**: Vue 3
- **图表**: [Mermaid](https://mermaid.js.org/)
- **公式**: [KaTeX](https://katex.org/)
- **部署**: GitHub Pages

## 🚀 快速开始

### 安装依赖

```bash
npm install
# 或者
yarn install
```

### 本地开发

启动本地开发服务器，实时预览修改：

```bash
npm run docs:dev
```

### 构建

生成静态文件到 `docs/.vitepress/dist`：

```bash
npm run docs:build
```

### 部署

运行部署脚本将构建后的文件发布到 GitHub 仓库：

```bash
./deploy.sh
```

## 📂 目录结构

```
.
├── docs/
│   ├── .vitepress/        # VitePress 配置与主题
│   ├── categories/        # 分类索引页
│   ├── posts/             # 文章 Markdown 源文件
│   ├── public/            # 静态资源 (图片、数据)
│   └── index.md           # 首页配置
├── scripts/               # 辅助脚本
└── package.json
```

## 📄 License

[Apache License 2.0](./LICENSE)
