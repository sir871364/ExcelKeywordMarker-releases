# ExcelKeywordMarker - Releases

此 repo 僅用於發布「Excel 自動標色工具」的更新檔（不含原始碼）。

- `version.txt`：目前最新版本號（供程式自動更新比對，走 CDN 免 API 額度）
- Releases 的 `ExcelKeywordMarker.exe` 資產：對應版本的執行檔

發布請在原始碼專案執行 `scripts/release.ps1 -Publish`（先上傳 Release，再更新 version.txt）。
