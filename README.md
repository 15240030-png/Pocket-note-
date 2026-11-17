# Pocket Notes｜隨身記事本

一個使用原生 HTML、CSS、JavaScript 製作的響應式記事本，可直接部署到 GitHub Pages。

## 功能
- 新增、編輯、刪除記事
- 依標題與內容搜尋
- 課業、生活、靈感、其他分類
- 收藏重要記事
- 自動儲存至瀏覽器 LocalStorage
- 深色／淺色模式
- JSON 備份匯出與匯入
- 手機、平板、桌面響應式介面

## 本機測試
直接用瀏覽器開啟 `index.html` 即可。也可以在資料夾執行：
```bash
python -m http.server 8000
```
再開啟 http://localhost:8000

## 發布到 GitHub Pages
1. 登入 GitHub，建立一個新的 Public repository，例如 `pocket-notes`。
2. 將 `index.html` 與 `README.md` 上傳到 repository 根目錄。
3. 開啟 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**。
5. Branch 選 `main`，資料夾選 `/(root)`，按 Save。
6. 等待 GitHub Pages 部署完成，網址通常是 `https://你的GitHub帳號.github.io/pocket-notes/`。

## 資料儲存提醒
記事存在目前瀏覽器的 LocalStorage，不會自動跨裝置同步。清除網站資料、瀏覽器資料或更換裝置前，請先使用「匯出備份」保存 JSON 檔。
