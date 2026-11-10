# 实习机会 · 名企实习直推

静态海报画廊网站：首页展示全部实习海报，支持按分类筛选、按公司名搜索，点击海报查看大图。

## 文件结构

- `index.html` — 网站首页（分类筛选 + 搜索 + 大图查看）
- `images/` — 海报图片（JPG）

## 发布到 GitHub Pages

1. 把本文件夹全部内容 push 到 GitHub 仓库 `gandlsuperuser/shixijihui` 的 main 分支（根目录放 `index.html`）。
2. 打开仓库 Settings → Pages → Build and deployment → Source 选择 **Deploy from a branch**，Branch 选择 **main**、文件夹 **/ (root)**，保存。
3. 等 1–2 分钟，访问 `https://gandlsuperuser.github.io/shixijihui/` 即可看到网站。

## 更新海报

新海报做好后，把图片放进 `images/`，并在 `index.html` 的 `POSTERS` 数组里加一行（name / file / cat），重新 push 即可。
