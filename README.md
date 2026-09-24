# yunyin

云韵音乐介绍页（GitHub Pages 静态站点）。

## 开启 Pages

1. 在 GitHub 新建仓库 `yunyin`（公开或私有均可）。
2. 推送本仓库代码到 `main` 分支。
3. 仓库 **Settings → Pages → Build and deployment**：Source 选 `Deploy from a branch`，Branch 选 `main` / `/ (root)`，保存。
4. 访问 `https://<用户名>.github.io/yunyin/` 即可。

> 仓库里已放 `.nojekyll`，避免 Jekyll 处理导致资源被忽略。

## 更新内容

只改 `index.html` 一个文件（样式、脚本、图标全部内联），改完提交推送，Pages 会在一分钟内自动更新。

## 本地预览

```bash
python -m http.server 8080
# 浏览器打开 http://localhost:8080
```
