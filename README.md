# PRD Prompt 產生器 v2.0

> 金融業 PM 協作工具 · Financial PM Collaboration Tool

業務 PM 與產品 PM 共同填寫需求，整合產出 AI 可讀的 PRD Prompt，直接複製至 Claude / ChatGPT 使用。

🔗 **[線上使用](https://judy15649.github.io/prd-prompt-generator)**

---

## 功能特色

- **業務 PM 輸入**：業務背景、業管法遵（AML/KYC）、業務策略、KPI 指標
- **產品 PM 輸入**：產品發展方向、UX 目標、電文/API 規格、平台需求
- **業務文件上傳**：支援 `.txt`、`.md` 拖曳上傳，自動擷取內容整合進 Prompt
- **共同設定**：PRD 段落選擇、優先級、時程、AI 輸出語言與詳細程度
- **一鍵產生**：整合兩方輸入，呼叫 Claude AI 產出結構化 PRD Prompt
- **複製 / 下載**：支援複製全文與下載 `.txt` 檔案
- **RWD 響應式**：支援桌面與行動裝置

---

## 使用方式

### 線上版（GitHub Pages）

直接開啟網址即可使用，無需安裝任何套件。

### 本地端

```bash
# clone 專案
git clone https://github.com/judy15649/prd-prompt-generator.git

# 直接用瀏覽器開啟
open index.html
```

---

## 五步驟流程

```
Step 1  業務 PM 輸入   →   Step 2  產品 PM 輸入
                                    ↓
Step 5  PRD Prompt   ←   Step 4  確認 & 產生   ←   Step 3  共同設定
```

---

## 技術說明

- 純前端 HTML/CSS/JS，無後端依賴
- AI 產生功能使用 [Anthropic Claude API](https://docs.anthropic.com)（需在 claude.ai 環境下使用）
- 若 API 無法連線，自動切換為結構化模板輸出，功能不中斷

---

## 版本紀錄

| 版本 | 日期 | 變更內容 |
|------|------|---------|
| v2.0 | 2026-03-27 | 修正 PRD 段落選擇 toggleChip bug |
| v1.0 | 2026-03-20 | 初始版本發布 |

---

## 授權

內部使用 · Internal Use Only
