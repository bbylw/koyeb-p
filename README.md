# WebNav Hub

WebNav Hub 是一个现代化的、响应式的单页静态导航网站，旨在收集和整理互联网上常用的优质资源。它采用了深色模式设计，提供平滑的滚动体验和直观的分类导航。

## ✨ 特性

- **响应式设计**：完美适配桌面、平板和移动设备。
- **深色模式**：默认采用护眼的深色主题，极具科技感。
- **平滑滚动**：点击导航菜单可平滑滚动至对应分类。
- **分类清晰**：资源按类别分组（AI搜索、社交媒体、实用工具等），查找方便。
- **轻量级**：纯静态页面，无复杂依赖，加载速度快。
- **Node.js 支持**：配置了 `package.json`，支持通过 Node.js 环境快速部署（如 Koyeb）。

## 🛠️ 技术栈

- **HTML5**: 语义化的页面结构。
- **CSS3**: 使用 CSS 变量管理主题，Flexbox 和 Grid 布局实现响应式排版。
- **JavaScript**: 原生 JS 实现交互逻辑（导航高亮、平滑滚动）。
- **Font Awesome**: 提供丰富的图标支持。
- **Node.js & Serve**: 使用 `serve` 包提供静态资源服务。

## 🚀 快速开始

### 本地运行 (直接打开)

由于是纯静态文件，你可以直接双击 `index.html` 在浏览器中打开即可预览。

### 本地运行 (Node.js)

如果你想在本地模拟服务器环境，可以使用 Node.js：

1.  **安装依赖**：
    ```bash
    npm install
    ```

2.  **启动服务**：
    ```bash
    npm start
    ```

3.  **访问**：
    打开浏览器访问 `http://localhost:3000`。

## 📦 部署指南

本项目已配置为 Node.js 项目，非常适合部署到支持 Buildpacks 的云平台，例如 **Koyeb**。

### 部署到 Koyeb

1.  **Fork 本仓库** 到你的 GitHub 账号。
2.  登录 [Koyeb 控制台](https://app.koyeb.com/)。
3.  点击 **Create App**。
4.  选择 **GitHub** 作为部署源。
5.  选择你 Fork 的 `webnav` 仓库。
6.  **重要**：在 **Builder** 设置中，选择 **Buildpacks** (通常是默认值)。
    *   Koyeb 会自动检测到 `package.json` 并使用 Node.js 构建。
    *   **不要**选择 Docker。
7.  点击 **Deploy**。
8.  等待构建完成，你的导航站就上线了！

## 📂 项目结构

```
.
├── index.html          # 主页面文件 (包含 HTML, CSS, JS)
├── package.json        # Node.js 项目配置文件
└── README.md           # 项目说明文档
```

## 📝 许可证

本项目开源，欢迎学习和交流。
