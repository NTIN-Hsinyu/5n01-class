五護101班 PWA 第一版

檔案：
- index.html：主頁
- manifest.webmanifest：PWA 安裝資訊
- sw.js：離線快取 Service Worker
- icon-192.png / icon-512.png：App 圖示

測試方式：
1. 將整個資料夾部署到 HTTPS 網站（例如 Netlify）。
2. Android：Chrome 開啟後可安裝/加入主畫面。
3. iPhone：Safari → 分享 → 加入主畫面。
4. Service Worker 必須透過 HTTPS 或 localhost 才能正常運作；直接雙擊本機 HTML 不會完整啟用 PWA。

目前尚未加入：
- Google Sheets 公告資料
- Google Calendar 同步
- Web Push 推播後端
