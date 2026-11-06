# NLP 自然語言處理 (115 S1) - 課程專案

本專案為 NLP 課程開發環境與實作練習區。

---

## 開發者資訊 (Developer Info)
* **學號**：[U12627003]
* **姓名**：[王威翔]

## 硬體與環境狀態 (Environment Setup)
* **PyTorch 執行環境**：[Windows CPU]

---

## 課程任務清單 (Task Checklist)

### Week 2：開發環境與專案架構初始化
請在完成下列任務後，將 `[ ]` 改為 `[x]`：
- [x] 成功建立 GitHub 帳號並 Clone 本專案至本機端。
- [x] 成功建立 `.venv` 虛擬環境，並透過 `.gitignore` 隱藏底層檔案。
- [x] 成功於虛擬環境內安裝通用套件清單 (`requirements.txt`) 與專屬硬體版本的 PyTorch。
- [x] 更新本 README 文件，填寫學號、姓名與 PyTorch 環境狀態。
- [x] 成功使用 Git 完成 `commit` 並 `push` 同步至 GitHub 雲端。

### Week 4 / 8: Data Ingestion & Topology-Aware Chunking
- [x] **環境建置與版控防護**：更新 `.gitignore` 成功阻擋原始 PDF 與暫存 JSON，並保留 `.keep` 目錄結構。
- [x] **資料擷取與合併**：任務 1-A 頁首頁尾清除、1-B 雙語標題合併、1-C 雙語條文合併 (完成者分別打勾)。
  - [x] 1-A
  - [x] 1-B
  - [x] 1-C
- [x] **結構健全度 (Mechanical Sanity)**：
  - [x] 拓撲錨定率
  - [x] 運用「中位數 (Median)」計算文本長度。
- [x] **語意品質 (Semantic Quality)**：
  - [x] (選修) 成功計算 Shannon Information Entropy (夏農資訊熵)，比較 Cleaned 與 Raw 資料的中位數資訊熵。
- [x] **觀測儀表板與報告**：
  - [x] 成功繪製 4 拼圖資料觀測儀表板 (4-Panel Dashboard)。
  - [x] 成功將核心評估指標匯出為根目錄下的 `metrics.json`。

---

### Week 08：PDF 資料輸入與前處理（Data Ingestion）

- [x] 完成 Python 虛擬環境與 Docling 套件設定。
- [x] 成功解析 9 份 PDF 文件。
- [x] 完成 PDF 批次資料擷取。
- [x] 產生 Raw Markdown 原始文件。
- [x] 完成 Markdown 清洗與格式整理。
- [x] 產生 Cleaned Markdown 清洗文件。
- [x] 完成 1-A：頁首頁尾清除。
- [x] 完成 1-B：雙語標題合併。
- [x] 完成 1-C：雙語條文合併。
- [x] 完成 Raw 與 Cleaned Chunk 建立。
- [x] 匯出 Raw JSON 與 Cleaned JSON。
- [x] 完成資料品質指標分析。
- [x] 完成 4-Panel Dashboard。
- [x] 匯出 metrics.json。

---

### Week 09：期中考資料前處理與分析報告

- [x] 完成 9 份 PDF 文件批次處理。
- [x] 統計三大類別 Raw 與 Cleaned Chunk 數量。
- [x] 完成 410 個 Raw 與 385 個 Cleaned Chunk 統計。
- [x] 完成指定 Long Chunk 分析。
- [x] 完成指定 Low Entropy Chunk 分析。
- [x] 完成驗證碼與文件行號查證。
- [x] 完成資料清洗異常案例分析。
- [x] 完成人工查證與 AI 分析比較。
- [x] 完成 DATA_REPORT.md 期中考報告。
- [x] 完成 AI_USAGE.md AI 協作紀錄。
- [x] 完成 09_midterm_chunks.ipynb 並保留執行結果。