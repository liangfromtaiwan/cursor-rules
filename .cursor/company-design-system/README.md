# 公司設計系統（company-design-system/）

本資料夾位於 **`.cursor/company-design-system/`**，為專案內唯一設計系統來源（與 `.cursor/rules` 同屬 `.cursor`，請勿在專案根目錄重複放置）。  
以下為公司設計系統的 **token 與規範來源**，供在 Cursor 內產出「代表公司」的產品時使用（POC、admin、platform、後台等）。

---

## 資料夾內容

| 項目 | 說明 |
|------|------|
| **all-variables.css** | 公司唯一 design tokens 來源（顏色、間距、圓角、語意 token `--sem-*` 等）。實作時必須引入，且**禁止硬編碼**色碼或魔術數字。 |
| **Claude-design-system-updates-2026-02-20.md** | 元件規格更新與使用指南（Sidebar、Header、Drawer、網格、token 優先順序、驗收檢查表）。 |
| **ux-writing.md** | UX writing 規則：英文／日文介面文案必讀文件路徑與摘要。 |
| **design-examples/** | 設計範例：`Platform example`、`Learner example`（可下載給同事參考）。 |
| **ux-writing-guidelines/** | UX 撰寫指南：`English`（Platform UX Writing Guideline）、`日本語`（ガイドライン・用語索引）。 |
| **scalar-branding-override.css** | Scalar API 文件品牌覆寫（僅顏色與字型）。搭配規則 `.cursor/rules/scalar-api-docs-branding.mdc` 使用。 |
| **README.md** | 本說明。 |

---

## 在 Cursor 裡怎麼用

1. 啟用規則 **「company-design-system」**（`.cursor/rules/company-design-system.mdc`）。  
2. 在專案中引入 **`company-design-system/all-variables.css`**（路徑依專案調整）。  
3. 顏色、間距、圓角、字級等皆使用該檔案內變數，優先順序：**`--sem-*` → `--tokens-*` → `--spacing-*` / `--radius-*` → `--colors-*`**。

---

## 快速參考（Admin / Platform）

| 元件 | 規格 |
|------|------|
| Sidebar 寬度 | 展開 256px、收合 64px |
| Sidebar 背景／邊框 | `var(--colors-sand-1)` / `var(--colors-sand-3)` |
| Header 高度／背景 | 56px / `var(--colors-sand-1)` |
| Drawer 寬度 | 720px |
| Dialog | Small 400px / Medium 600px / Large 800px |
| 版面 | 12 欄網格，僅允許 span 12 / 8 / 6 / 4 / 3 |

細節見 **Claude-design-system-updates-2026-02-20.md**。  
Platform／Learner 範例：**`.cursor/company-design-system/design-examples/Platform example`**、**`Learner example`**。  
英文／日文 UX 指南：**`.cursor/company-design-system/ux-writing-guidelines/English`**、**`日本語`**。
