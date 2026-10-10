# tw-market-images

台股盤後快報（LINE 推播）用的圖片暫存區。

- 圖片放在 `img/`，檔名格式為 `YYYYMMDD-HHMMSS_<名稱>`（台北時間）。
- 保留約一天（24 小時）後自動刪除；每次上傳或清理時都會以一個全新的 orphan commit 強制推送到 `main`，因此已刪除的圖片不會留在 git 歷史中。
- 圖片網址：`https://raw.githubusercontent.com/kuangame/tw-market-images/main/img/<檔名>`

此 repo 由自動化腳本管理，請勿手動提交。
