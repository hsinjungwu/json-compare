# JSON 差異比對工具 (JSON Diff Tool)

一個輕量、快速且基於瀏覽器的 JSON 差異比對工具。專為開發者設計，支援遞迴收合、差異標註以及 GitHub Pages 快速部署。

## 🌟 特色功能
- 雙欄對照比對：清晰的左（Before）右（After）對照介面。
- 差異高亮標示：
    - 紅色高亮：顯示在左側，代表被刪除或修改前的資料。
    - 綠色高亮：顯示在右側，代表新增或修改後的資料。
- 遞迴收合節點：支援複雜、深層嵌套的 JSON 結構，點擊箭頭即可輕鬆展開或收合。
- 單檔案設計：完全基於一個 HTML 檔案，不需安裝 npm 或 node_modules，適合快速自用。
- 響應式介面：自動適應電腦與手機螢幕。

## 🚀 快速部署到 GitHub Pages
這是一個純靜態網頁，您可以直接將 index.html 部署到 GitHub Pages：
1. 在 GitHub 上建立一個新的儲存庫 (Repository)。
2. 將專案中的 index.html 上傳至該儲存庫。
3. 進入儲存庫的 Settings > Pages。
4. 在 Build and deployment 部分，確保 Source 選擇為 Deploy from a branch。
5. 選擇 main 分支並點擊 Save。
6. 完成！幾分鐘後，您的專案將運行在 https://<您的帳號>.github.io/<專案名稱>/。

## 🛠️ 使用技術
- React (透過 CDN 載入)
- Tailwind CSS (快速 UI 排版)
- Babel (瀏覽器端 JSX 編譯)
- Lucide Icons (向量圖示)

## 📝 使用說明
1. 在左側文字方塊貼上原始的 JSON。
2. 在右側文字方塊貼上修改後的 JSON。
3. 點擊 「開始比對」 按鈕。
4. 在下方結果區查看差異，您可以點擊藍色括號旁邊的箭頭來展開或隱藏特定的 JSON 層級。

----
*此專案由 AI 輔助開發，旨在提供極簡且高效的開發輔助工具。*