# Kai Grade NEXT V1.5
讓每一筆成績，都成為進步的依據。

## 部署
將本專案所有檔案與資料夾上傳至 GitHub repository 的 `main` 分支根目錄，然後在 Settings → Pages 將 Build and deployment 設為 **GitHub Actions**。推送後由 Actions 部署。

## 已實作功能
- 響應式 UI、深色／淺色模式
- 成績新增、編輯、刪除、搜尋、CSV 匯出
- 考試新增、編輯、封存、刪除
- 錯題練習庫、學習任務、筆記中心
- 整體與各科平均統計、學期彙整與列印
- IndexedDB 本機資料保存、JSON 備份與還原
- PWA manifest、Service Worker 基本離線快取
- GitHub Actions GitHub Pages 部署流程

## 資料安全
資料存在目前瀏覽器的 IndexedDB，不會自動跨裝置同步。請定期下載 JSON 備份。不要在公開前端程式碼中放入 GitHub Token、密碼或私人資料。

## 尚未包含
雲端同步與衝突解決、推播通知、XLSX 匯入、生成式 AI、完整操作歷史、自動備份與完整自動化測試尚未實作。本版的分析是規則統計，不是生成式 AI。
