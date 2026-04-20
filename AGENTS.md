# Project Notes

## 2026-04-20

- GitHub Pages 根站地址 `https://robostream123.github.io/` 实际由仓库 `RoboStream123/RoboStream123.github.io` 提供，而不是直接从当前仓库根地址发布。
- 根站仓库的工作流文件是 `.github/workflows/deploy-pages.yml`，会在发布时拉取当前仓库 `RoboStream123/Robostream_website` 的 `main` 分支内容并部署到 Pages。
- 已为根站工作流补充定时同步触发；当前根站仓库提交为 `cd81755`，后续会按 10 分钟周期自动同步当前仓库的最新内容。
- 当前仓库最近一次与页面内容相关的提交为 `efcbeea`，包含 `Yuzhi Huang` 的机构更新。
