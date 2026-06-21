# apps-haobosports-pages

## 项目简介

本仓库用于归档和发布多个独立的 HTML 页面。这些页面以静态文件形式存放，不依赖特定域名或后端服务，方便直接通过 GitHub Pages 或其他静态托管平台访问。

## 目录说明

```
apps-haobosports-pages/
├── pages/          # 存放各独立 HTML 页面及相关资源
│   ├── page-a/
│   ├── page-b/
│   └── ...
├── assets/         # 公共资源文件（CSS、JS、图片等）
├── index.html      # 仓库首页（可选）
└── README.md       # 本文件
```

- `pages/`：每个子目录对应一个独立的 HTML 页面，包含其所需的 HTML、CSS、JavaScript 及图片等资源。
- `assets/`：存放多个页面共用的资源文件，减少重复。

## 页面归档说明

每个页面均为独立完整的 HTML 文件，可直接在浏览器中打开运行。归档的页面可能包含：

- 简单工具页面
- 信息展示页面
- 交互式原型
- 其他静态演示页面

页面之间没有依赖关系，可独立部署或引用。

## 使用方式

1. 克隆本仓库到本地：
   ```bash
   git clone https://github.com/your-username/apps-haobosports-pages.git
   ```
2. 直接在浏览器中打开 `pages/` 下对应子目录中的 HTML 文件即可查看。
3. 如需部署到 GitHub Pages，可启用仓库的 Pages 功能，并将源设置为 `main` 分支的根目录。

## 维护说明

- 新增页面：在 `pages/` 下创建新目录，放入 HTML 及相关文件，并在 `index.html` 中添加链接（可选）。
- 更新页面：直接修改对应目录下的文件，提交并推送。
- 删除页面：移除对应目录，并更新索引文件（如有）。
- 请保持目录结构清晰，避免文件冗余。

## 贡献

欢迎提交 Issue 或 Pull Request 来改进本仓库。请确保新增或修改的页面为独立的 HTML 文件，不包含外部敏感链接。

## 许可

本仓库内容仅供学习与参考，具体许可请参见仓库中的 LICENSE 文件（如有）。
