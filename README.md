# 文稿影片產生器 (ScriptStudio)

單一檔案靜態網頁，由 `upload.html` 原封不動改名為 `index.html` 上架 GitHub Pages。

- 開啟方式：用 Chrome / Edge 開啟 Pages 連結即可，不需安裝。
- 語音辨識：首次使用需連網下載 Whisper 模型（預設 base，約 77 MB），之後快取在瀏覽器 IndexedDB，可離線使用；也可匯入離線語音包。
- 注意：GitHub Pages 無法自訂 COOP / COEP 標頭，多執行緒 WASM 可能退回單執行緒，辨識會慢一點，但仍可使用。
