# kk-tools — KK 的工具總專案

## 對話開始時請先讀
進度與最近更動都在 Obsidian：`secondbrain/kk-tools/工作筆記.md`

## 工作模式
- **加新工具**：對 Claude 說「我想做一個 XXX 工具」→ Claude 會建 `tools/<工具名>/` 子資料夾、引導我跟著影片做
- **結束工作**：對 Claude 說「**收工**」→ 自動 commit + push + 更新 Obsidian 工作筆記
- **接續工作**：對 Claude 說「**開工**」→ 讀工作筆記、報告 git 狀態、建議下一步

## 工作桌 + 三個家
- 📋 GDrive 工作桌：`G:\我的雲端硬碟\kk-tools\`（自動跨電腦同步）
- 🐙 GitHub repo：`YUAN-5149/kk-tools`（公開，網頁的家）
- 📘 Obsidian 駕駛艙：`secondbrain/kk-tools/工作筆記.md`（想法的家）
- 🔥 Firebase 專案：`home-yuan`（Standard 版 Firestore，asia-east1，資料的家）

## 工具清單
（之後加新工具時會自動更新）
- （尚無）

## 工作注意事項
- 學生 / 學員資料一律去識別化（只用座號 / 編號 + 班級代號）
- commit 訊息要寫清楚做了什麼 + 為什麼
- 收工前說「收工」讓 Claude 同步三方
- 新增 Firestore 集合時要寫 Security Rules（白名單）

## 相關工具
- AI：本地無 Ollama（RAM 不夠），雲端用 **Gemini 2.5 Flash 免費 API**（環境變數 `GEMINI_API_KEY`）
