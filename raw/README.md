# Raw Sources

把原始素材放在這個資料夾。**這層不可變**——LLM 只讀不改。

## 可放入的格式

- `.md` / `.txt`：文章、筆記、逐字稿
- `.pdf`：研究報告、書摘、財報
- `.html`：網頁存檔
- `.csv` / `.json`：數據
- `.png` / `.jpg`：圖表、截圖（LLM 可讀）

## 命名建議

`YYYY-MM-DD_作者_標題簡述.ext`

例：
- `2026-04-15_buffett_2025-shareholder-letter.pdf`
- `2026-03-02_bloomberg_fed-rate-decision.md`
- `2026-01-20_my-notes_etf-tax-thoughts.md`

## 加入新素材後

對 Claude Code 說：「ingest 最新放進去的檔案」，或指明檔名。
