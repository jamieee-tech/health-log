# 🏃‍♂️ 健康日誌 · FitTrack Pro

個人運動與飲食整合紀錄網頁，部署於 GitHub Pages。

## 功能
- 運動與飲食日誌（Firebase Firestore 雲端同步）
- 體重 / 體脂趨勢圖（Chart.js）
- 飲水紀錄與蛋白質進度條
- Excel 匯出報表
- 密碼保護（本地驗證 + 24 小時 Session）

## 技術棧
- 純 HTML / CSS / JS（無框架）
- Firebase Firestore（資料儲存）
- Chart.js（趨勢圖）
- SheetJS XLSX（Excel 匯出）
- Google Fonts — Inter + Outfit

## 本地開發
直接用瀏覽器開啟 `index.html` 即可（需要 HTTPS 或 localhost，Firebase ES Module 不支援 file:// 協議）。

```bash
# 快速啟動本地 HTTPS-free 伺服器（需 Node.js）
npx serve .
```
