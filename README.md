# NightGuard AppPages (GitHub Pages 指南 / Guide)

本目录包含可直接用于 GitHub Pages 的静态内容：
- `privacy.md`：隐私政策（中英文）
- `support.md`：技术支持/帮助（中英文）
- `index.md`：索引页

## 使用方式（方案一：单独站点仓库，推荐）
1) 在本地复制本目录作为独立站点文件夹（例如 `nightguard-site`）：
```bash
echo "在桌面创建 nightguard-site"
cp -R "$(pwd)/AppPages" "$HOME/Desktop/nightguard-site"
cd "$HOME/Desktop/nightguard-site"
```
2) 初始化 git 并提交：
```bash
git init
git add .
git commit -m "Add NightGuard site (privacy & support)"
```
3) 在 GitHub 新建一个仓库（命名建议：`nightguard-site`），然后把远程地址换成你的：
```bash
git branch -M main
git remote add origin https://github.com/<YOUR_GH_USERNAME>/nightguard-site.git
git push -u origin main
```
4) 启用 GitHub Pages：
- 打开仓库 Settings > Pages  
- Source: `Deploy from a branch`  
- Branch: `main`，Folder: `/root`  
- 保存后获得站点 URL，例如：`https://<YOUR_GH_USERNAME>.github.io/nightguard-site/`

5) 提交给 App Store Connect：
- App Support URL: `https://<YOUR_GH_USERNAME>.github.io/nightguard-site/support`（或 `.html`/`.md` 渲染后的稳定链接）
- Privacy Policy URL: `https://<YOUR_GH_USERNAME>.github.io/nightguard-site/privacy`

> 如果 Pages 未渲染 `.md` 为 HTML，可在浏览器中直接访问 `.md` 链接，或将 `.md` 转为 `.html` 并更新链接。

## 使用方式（方案二：保留在现有仓库的 /docs）
1) 将本目录复制/移动到你的任意仓库的 `/docs`：
```bash
cp -R "$(pwd)/AppPages" /path/to/your/repo/docs
```
2) 在该仓库启用 Pages：
- Settings > Pages > Source: `Deploy from a branch`  
- Branch: `main`，Folder: `/docs`  
- 最终 URL 形如：`https://<YOUR_GH_USERNAME>.github.io/<REPO_NAME>/`

## 自定义域（可选）
1) 购买或使用现有域名（例如 `nightguard.vectrakode.com`）。  
2) 将域名的 CNAME 指向 `<YOUR_GH_USERNAME>.github.io`。  
3) 在 Pages 设置里添加该域名并启用 HTTPS。  
4) 最终 URL 示例：
- Privacy: `https://nightguard.vectrakode.com/privacy`
- Support: `https://nightguard.vectrakode.com/support`

## 维护建议
- 每次修改政策请更新文件顶部的 `Last Updated` 日期。
- 保持邮箱统一：`NightGuard@vectrakode.com`。
- 建议保留英文与中文两种语言内容以提升审核通过率与用户可读性。


