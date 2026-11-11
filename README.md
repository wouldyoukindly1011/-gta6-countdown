# GTA VI — Vice City Countdown

這是一個個人粉絲自製的 iPhone 主畫面倒數 PWA。

## 安裝方式
iOS 的「加入主畫面」需要透過 HTTPS 網址開啟，單純把 HTML 存在 iPhone 檔案 App 裡通常不能完整安裝成離線 PWA。

### 最簡單的免費部署方式：GitHub Pages
1. 在 GitHub 建立一個新的公開 repository。
2. 將本資料夾內的 `index.html`、`manifest.webmanifest`、`sw.js`、`icon-192.png`、`icon-512.png` 上傳到 repository 根目錄。
3. 到 repository 的 Settings → Pages。
4. 在 Build and deployment 選擇 Deploy from a branch，Branch 選 `main`、資料夾選 `/(root)`，按 Save。
5. 等待 GitHub Pages 提供 HTTPS 網址。
6. 用 iPhone Safari 開啟該網址 → 分享 → 加入主畫面 → 新增。

## 功能
- 以台灣裝置當地時間倒數至 2026-11-19 00:00
- 每秒更新天／時／分／秒
- 可在「設定日期」自行調整目標日期
- PWA 快取，部署後可離線開啟
- iPhone 主畫面圖示與獨立視窗顯示

此為非官方粉絲作品，未使用 Rockstar 官方商標圖檔或遊戲素材。
