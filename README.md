# PromptVault · AI 提示語資料庫

收藏與組合 AI 繪圖提示語：內建範例庫、模組化組合器、AI 擴寫，可匯入匯出 JSON。

**線上使用**：https://kftseng2oo1.github.io/prompt/

## 主要功能
- **資料庫**：內建範例（商品攝影、霓虹夜景、Logo、人像、3D 黏土、電商 Banner、海報、室內設計…），可搜尋、分類篩選、收藏
- 每筆有正向／負向提示語與版本修改紀錄，一鍵複製
- **🔧 模組化組合器**：挑選主題、風格、光線等模組並調整權重，設定比例與語言，即時預覽
- **✦ AI 擴寫**：用 Claude 把簡短提示擴寫成完整提示
- 自建提示語可存入資料庫；匯出／匯入 JSON

## 技術與依賴
- 單檔 HTML PWA（`index.html` 內含全部 HTML/CSS/JS），`manifest.json` + `sw.js` 提供安裝到主畫面與離線快取。
- Claude 直連 `api.anthropic.com`（需自備 API Key）
- 本機資料：`pv_apikey`、`pv_custom`、`pv_favs`、`pv_built`、`pv_copies`

## 備註
- `prompt-library.html` 是較舊的版本（約 131 KB，`index.html` 約 149 KB），確認後可刪除。
- 相關：[ai-pmp](https://github.com/kftseng2oo1/ai-pmp)（依照片生成人像提示詞）
