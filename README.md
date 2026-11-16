# K-pop 收藏小卡與保存指南 Wiki

整理 K-pop 小卡（photocard）收藏、卡膜與卡套、A4/A5 收集冊、壓克力展示櫃、7-ELEVEN 賣貨便包裝與寄送的知識型靜態網站。

- 技術：純 HTML + Tailwind CSS（CDN），無打包工具、無框架
- 開發規範：請先閱讀 [AGENTS.md](AGENTS.md)
- 在地預覽：直接用瀏覽器開啟 `index.html`

## 部署到 GitHub Pages
1. 將整個資料夾推到 GitHub repository 的 `main` 分支根目錄。
2. 到 Settings → Pages，Source 選 `Deploy from a branch`，Branch 選 `main`、資料夾選 `/ (root)`。
3. 等待部署完成後，用 Pages 提供的網址瀏覽。所有連結皆為相對路徑。

## 新增頁面
依 AGENTS.md 第 6 節：複製 `pages/_template.html` → 填內容 → 所有 HTML 側邊欄加連結 → `index.html` 加卡片 → 檢查。
