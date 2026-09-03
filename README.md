# PISEN AI Lab 官网原型

硬件官网（index.html，主页面）+ 软件官网（software.html）静态交互原型。

## 部署到 GitHub Pages 步骤

1. 在 GitHub 上新建一个仓库（Public），例如 `pisen-ai-lab-site`。
2. 在本目录下执行：

   ```bash
   git init
   git add .
   git commit -m "Initial commit: PISEN AI Lab site prototype"
   git branch -M main
   git remote add origin https://github.com/<你的用户名>/pisen-ai-lab-site.git
   git push -u origin main
   ```

3. 打开仓库页面 → **Settings** → **Pages** → Source 选择 **Deploy from a branch**，Branch 选择 `main` / `/ (root)`，保存。
4. 等待 1–2 分钟，访问 `https://<你的用户名>.github.io/pisen-ai-lab-site/` 即可看到硬件官网主页；软件页地址为 `.../software.html`。

> 也可以用 GitHub 网页端直接上传：仓库页面 → Add file → Upload files → 把本目录两个 html 文件拖进去提交，然后按第 3 步开启 Pages。

## 文件说明

- `index.html` — 硬件官网（主页面）：硬件轮播 / APP 简介入口 / AI 硬件产品功能 / 团队职能+合作咨询
- `software.html` — 软件官网：APP 简介 / APP 功能矩阵 / 订阅云服务

两个文件必须放在同一目录，硬件页通过「了解 App 详情」按钮跳转到软件页。
