# ⏱️ OT 打卡月曆冊 (OT Calendar Tracker)

這是一個專為追蹤 OT（加班）設計的**月曆介面打卡網站**。適合擺喺 GitHub Pages 隨時用手機開啟打卡！

## ✨ 主要特色
- 🗓️ **月曆視圖**：一眼睇晒邊一日有 OT，月曆格仔內自動顯示 **+$100** 標籤及打卡相片縮圖。
- 📸 **打卡相片上傳**：點擊任何日子即可上傳打卡證明照片，系統自動壓縮圖片（節省容量）。
- 📊 **按週自動結算**：自動按 ISO 週數計算每一週 OT 有幾多天、小計幾多錢（1 天 = $100）。
- 🔒 **資料私隱無憂**：所有記錄只儲存在手機/電腦本地瀏覽器（LocalStorage），不會上傳到任何第三方伺服器。
- 💾 **資料備份與匯入**：提供 JSON 備份檔匯出/匯入功能，換手機亦能輕鬆轉移資料。

## 🚀 GitHub Pages 部署方法
1. 將本 Repository 設為 **Private** 或 Public。
2. 上傳 `index.html` 及 `README.md` 到主分支（`main` 或 `master`）。
3. 前往 Repository 的 **Settings** -> **Pages**。
4. Source 選擇 `Deploy from a branch`，Branch 選擇 `main` / `/(root)`，點擊 **Save**。
5. 幾分鐘後即可透過專屬網址開啟網站！
