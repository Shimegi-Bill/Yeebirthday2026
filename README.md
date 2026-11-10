# 雞髀大胃王 · 跑去抱媽咪

送俾二家姐 2026 年生日嘅手機網頁小遊戲。由 Bill Chiu 開發。

## 點樣玩
- 手指拖住雞髀，左右前後咁行
- 食晒天上跌落嚟嘅好嘢（🎂 一個當三個）
- 食夠 15 樣：由爬變行；食夠 40 樣：由行變跑
- 60 秒後，雞髀會跑去抱媽咪，之後唱生日歌

## 檔案
- `index.html`：成個遊戲（HTML、CSS、JavaScript 喺同一個檔）
- `manifest.json`、`apple-touch-icon.png`、`icon-192.png`、`icon-512.png`：加到主畫面用

## 改設定
- `index.html` 入面 `CFG`：名、時間、幾多樣先識行／識跑
- `FOODS`：雞髀鍾意食嘅嘢（emoji 同名）
- 每次上載新版本，記得改 `<head>` 入面 `window.__GB_VER` 嘅版本號（日期-次數），手機先會自動攞新版

## 放上網（GitHub Pages）
Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save，等 1–2 分鐘。
