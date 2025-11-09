# Nav 官方网站

Nav 项目的官方主页，使用 Astro 构建。

- 🌐 **在线预览**: https://bookmark.lllh.de/
- 📦 **GitHub 仓库**: https://github.com/deerwan/nav
- 🚀 **项目主页**: 本仓库 (nav-docs)

## 🚀 快速开始

### 安装依赖

```bash
npm install
```

### 开发服务器

```bash
npm run dev
```

开发服务器将在 `http://localhost:4321` 启动。

### 构建

```bash
npm run build
```

构建产物将输出到 `dist/` 目录。

### 预览构建结果

```bash
npm run preview
```

## 📁 项目结构

```
/
├── public/          # 静态资源
├── src/
│   ├── layouts/     # 布局组件
│   │   └── Layout.astro
│   └── pages/       # 页面
│       └── index.astro
├── astro.config.mjs # Astro 配置
├── tailwind.config.mjs # Tailwind CSS 配置
└── package.json
```

## 🛠️ 技术栈

- [Astro](https://astro.build) - 静态站点生成器
- [Tailwind CSS](https://tailwindcss.com) - 实用优先的 CSS 框架
- TypeScript - 类型安全

## 📝 开发

### 添加新页面

在 `src/pages/` 目录下创建新的 `.astro` 文件即可自动创建路由。

### 添加组件

在 `src/components/` 目录下创建组件，然后在页面中导入使用。

## 📄 许可证

与 Nav 主项目保持一致。
