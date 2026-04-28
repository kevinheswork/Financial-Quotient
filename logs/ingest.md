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

## 2026-04-28 — ingest 第二批兩篇

- 類型：article × 2
  - [[raw/2-3 兩個小招數讓你擁有理財情商.md]]
  - [[raw/3-1 不要用「一定掛」的觀念投資.md]]
- 新增頁（7）：
  - Concepts：[[wiki/concepts/複利與雪球公式.md]]、[[wiki/concepts/理性與耐心.md]]、[[wiki/concepts/戀愛腦風險.md]]、[[wiki/concepts/三大致命操作.md]]、[[wiki/concepts/緊急預備金.md]]
  - Entities：[[wiki/entities/查理蒙格.md]]
  - Syntheses：[[wiki/syntheses/投機者破產警世錄.md]]
- 更新頁（5）：
  - [[wiki/entities/巴菲特.md]]：補充 99.9% 財富在 50 歲後、90→95 歲財富 735→1400 億美元、「沒人想慢慢變富有」、避雷母原則
  - [[wiki/concepts/年化報酬率基準.md]]：新增「矛盾觀點」區塊（11% vs 12%）
  - [[wiki/concepts/三大投資心理障礙.md]]：障礙二補充少年股神 2025 清明節案例
  - [[wiki/syntheses/散戶致敗的心理路徑.md]]：補充 2-3、3-1 對「急」的回應與外顯
  - [[wiki/README.md]]：索引重寫
- 矛盾（1）：
  - **市值型 ETF 年化 11% vs 12%**：3-1 寫 11%，2-2 與既有 0050 頁寫 12%。可能來自時間區間 / 含息與否 / 0050 vs 廣義市值型 ETF 的差異。記錄於 [[wiki/concepts/年化報酬率基準.md]]，待使用者裁定或後續素材澄清。
- 備註：
  - 2-3 引入了講者首次正面提出的「正解方法論」——耐心 + 理性雙引擎，補上了上一輪 ingest 開放問題中的「如何降低急迫感」一部分。
  - 3-1 提供了大量歷史人物與當代案例（少年股神），新增的 [[wiki/syntheses/投機者破產警世錄.md]] 可作為未來其他「投機 / 槓桿」素材的接點。
  - 「貝佐斯」、「愛因斯坦」在 2-3 僅一句帶過，暫不立頁；「川普關稅效應」、「2025 清明節」是 3-1 的時事錨點，目前資訊不足以獨立成頁，已併入 [[wiki/concepts/三大致命操作.md]] 案例與 [[wiki/concepts/三大投資心理障礙.md]]。
