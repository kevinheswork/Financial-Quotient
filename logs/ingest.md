# Ingest Log

每次 ingest 一筆。格式：

```
## YYYY-MM-DD HH:MM — <來源檔名>
- 類型：article / book / transcript / data / note
- 新增頁：[[wiki/...]], ...
- 更新頁：[[wiki/...]], ...
- 矛盾：（若有）
- 備註：
```

---

## 2026-04-27 — 首次 ingest 三篇講者文章

- 類型：article × 3（同一講者 FQ 心態系列）
  - [[raw/1-1 没開始、賭運氣、想全贏.md]]
  - [[raw/2-1 停止抱怨！投錯胎也能成為富一代.md]]
  - [[raw/2-2 急著賺錢，只會遇到詐騙.md]]
- 新增頁（10）：
  - Concepts：[[wiki/concepts/三大投資心理障礙.md]]、[[wiki/concepts/定期定額.md]]、[[wiki/concepts/財富不可能三角.md]]、[[wiki/concepts/年化報酬率基準.md]]、[[wiki/concepts/詐騙心理機制.md]]、[[wiki/concepts/抱怨心態與富一代.md]]
  - Entities：[[wiki/entities/巴菲特.md]]、[[wiki/entities/0050.md]]、[[wiki/entities/大中華基金.md]]、[[wiki/entities/道瓊指數.md]]
  - Syntheses：[[wiki/syntheses/散戶致敗的心理路徑.md]]
- 更新頁：[[wiki/README.md]] 索引重寫
- 矛盾：無
- 備註：
  - 三篇素材來自同一講者（性別女性、曾任旅遊記者、45 歲產子，**素材未明示姓名**）；之後若 ingest 到署名素材，建議建立 `entities/講者.md` 並回填。
  - 開放問題集中於：巴菲特 13% 與 0050 12% 的精確時間區間、含息與否；大中華基金的具體標的；講者「降低急迫感」的方法論——皆需未來素材補齊。
  - 比特幣在 1-1 中被提及（為子女投資的另一標的），但細節極少，暫未立頁，待後續素材累積。
