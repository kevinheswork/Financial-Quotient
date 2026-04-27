# Financial Quotient — LLM Wiki

依 [Andrej Karpathy 的 LLM Wiki 模式](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) 建立的個人金融知識庫。

**核心想法**：不是 RAG 每次重切片，而是讓 LLM 把素材「編譯」進一座可讀、可交叉引用的 wiki，知識會**累積**而不是每次重新發現。

## 怎麼用

1. 把素材丟進 [`raw/`](raw/)。
2. 在這個資料夾打開 Claude Code，說「ingest 那個檔案」。
3. 之後直接問問題，Claude 會優先讀 [`wiki/`](wiki/) 回答。
4. 偶爾說「lint wiki」做健康檢查。

完整規範見 [CLAUDE.md](CLAUDE.md)。
