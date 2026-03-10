# RoboStream Website

这是一个可直接部署到 GitHub Pages 的静态项目网站，核心文件如下：

- `index.html`：页面结构与内容
- `assets/css/style.css`：样式与响应式布局
- `Figures/`：网页中使用的论文图表素材

## 本地预览

直接双击 `index.html` 即可打开，或在仓库根目录运行任意静态服务器：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## GitHub Pages 部署

1. 把当前目录推送到 GitHub 仓库（例如 `main` 分支）。
2. 进入仓库 `Settings` -> `Pages`。
3. `Build and deployment` 选择 `Deploy from a branch`。
4. 选择分支 `main`，目录选择 `/ (root)`，保存。
5. 等待 1-3 分钟后访问分配的站点地址。

## 发布前建议替换项

- `index.html` 中作者信息（当前是 `Anonymous Authors`）。
- 论文与代码链接（当前代码链接为 `Coming Soon`）。
- BibTeX 条目中的作者与最终会议信息。
