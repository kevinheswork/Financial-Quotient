# Lint Log

每次一致性檢查的結果清單，**不自動修**，等使用者裁定。

```
## YYYY-MM-DD — Lint pass
- 壞連結：
- 孤兒頁：
- 疑似重複：
- 缺來源的陳述：
- 數據衝突：
```

---

## 2026-04-28 — Lint pass（第二批 ingest 後）

掃描範圍：19 個 wiki 頁面、5 個 raw 素材。

### 壞連結
- 無。所有 `[[...]]` 連結皆指向實際存在的檔案。

### 孤兒頁
- 無。每個 wiki 頁面（除 `README.md` 索引本身）至少有 1 個 inbound 連結。

### 低連結頁（耦合偏弱，建議補連結）
- **[[wiki/concepts/緊急預備金.md]]**：僅 1 inbound（來自 [[wiki/concepts/三大致命操作.md]]）。建議從 [[wiki/syntheses/散戶致敗的心理路徑.md]] 與 [[wiki/concepts/複利與雪球公式.md]]（「不毀掉雪球」要素）補上反向連結。
- **[[wiki/entities/查理蒙格.md]]**：僅 1 inbound（來自 [[wiki/entities/巴菲特.md]]）。[[wiki/concepts/理性與耐心.md]] 與 [[wiki/concepts/三大致命操作.md]] 雖在文中提到蒙格，但**未使用 wikilink**，建議改成連結形式。

### 疑似重複 / 主題重疊
- [[wiki/concepts/三大投資心理障礙.md]] 障礙二（賭徒心態 / 迷信短期預測）與 [[wiki/concepts/三大致命操作.md]] 地雷二（追逐明牌）在「電枸杞 / 跟單」議題上有概念重疊。**建議保留兩頁**（前者談心態、後者談行為），但需在兩頁互相加強反向連結並標明分工。
- [[wiki/concepts/理性與耐心.md]] vs [[wiki/concepts/三大投資心理障礙.md]]：互為正反框架，已交叉連結，**不合併**。

### 數據衝突
- **市值型 ETF 年化 11%（[[raw/3-1 不要用「一定掛」的觀念投資.md]]） vs 12%（[[raw/2-2 急著賺錢，只會遇到詐騙.md]]、[[wiki/entities/0050.md]]）**。已於 [[wiki/concepts/年化報酬率基準.md]]「矛盾觀點」區塊記錄，**等使用者裁定**。
- 其餘數字（巴菲特 13%、道瓊 5.3%、定存 1.7%、巴菲特 99.9%/735→1400 億美元）皆只出現一個來源，無衝突。

### 缺來源 / 推論性陳述（建議標 ⚠️ 或補引）
- [[wiki/concepts/三大致命操作.md]]「核心邏輯」段：「在無法停止的賭局中，即使勝率有利，只要堅持 All-in，最終本金必歸零」——3-1 確有此意但用詞為改寫，已 cite，**OK**。
- [[wiki/concepts/複利與雪球公式.md]]「推論」一行（「早期看似成長緩慢是雪球的常態…」）——明確標為「推論」，且交叉指向已 cite 的概念頁，**OK 但可考慮加 ⚠️ 推論標籤**。
- [[wiki/entities/查理蒙格.md]]「對應概念頁」「與其他頁的關係」段落屬導覽，無事實陳述，**OK**。

### 已處理（2026-04-28）
1. ✅ **11% vs 12% 統一為 11%**：使用者裁定理由——百分點差異不重要，重點是複利機制。已更新 [[wiki/entities/0050.md]]、[[wiki/concepts/年化報酬率基準.md]]（保留歷史說明）、[[wiki/concepts/三大致命操作.md]]、[[wiki/entities/巴菲特.md]]、[[wiki/README.md]]。
2. ✅ **查理蒙格 inbound 補強**：[[wiki/concepts/理性與耐心.md]]、[[wiki/concepts/三大致命操作.md]] 將文中「蒙格」改為 wikilink。inbound 1 → 3。
3. ✅ **緊急預備金 inbound 補強**：[[wiki/concepts/複利與雪球公式.md]]（雪球三要素表格）、[[wiki/concepts/理性與耐心.md]]（物理基礎）、[[wiki/syntheses/散戶致敗的心理路徑.md]]（第四條解：物理底盤）。inbound 1 → 4。
