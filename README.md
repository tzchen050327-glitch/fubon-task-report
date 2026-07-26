# 悍將每週任務戰報 PWA

## 檔案
- `index.html`：主程式
- `manifest.webmanifest`：手機安裝資訊
- `sw.js`：離線快取
- `icon-192.png`、`icon-512.png`：Android / PWA 圖示
- `apple-touch-icon.png`：iPhone / iPad 主畫面圖示

## 重要
PWA 不能直接用手機開啟本機 HTML 安裝。請將整個資料夾部署到支援 HTTPS 的網站，例如 GitHub Pages。

## Android 安裝
1. 使用 Chrome 開啟部署後的網址。
2. 點網頁中的「安裝到手機」，或 Chrome 選單的「安裝應用程式／加到主畫面」。
3. 安裝後會以獨立視窗開啟。

## iPhone / iPad 安裝
1. 使用 Safari 開啟部署後的網址。
2. 點「分享」。
3. 選「加入主畫面」。
4. 從主畫面開啟後會以接近 App 的獨立模式顯示。

## 更新程式
若修改程式後手機仍顯示舊版本，請將 `sw.js` 中的 CACHE_NAME 版本往上調，例如：
`fubon-task-report-v2`
