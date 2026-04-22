# PTCG 卡组性格测试（GitHub Pages 部署包）

你这边访问 Vercel 超时，通常是网络/地区性不可用导致的；可以改用 GitHub Pages。

## 方式 A：纯手动（最简单）

1. 在 GitHub 新建一个仓库（比如 `ptcg-quiz`）
2. 上传本文件夹里的两个文件：
   - `index.html`
   - `.nojekyll`
3. 进入仓库 Settings → Pages
4. **Build and deployment** 选择 **Deploy from a branch**
5. Branch 选择 `main`，Folder 选择 `/ (root)`，保存
6. 等 1～2 分钟，会出现访问地址：
   `https://<你的用户名>.github.io/<仓库名>/`

## 方式 B：如果你想用 Actions（更规范）
我也可以再给你补一个 `.github/workflows/pages.yml`，实现每次 push 自动发布。

