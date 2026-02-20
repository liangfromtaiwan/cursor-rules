# cursor-rules

公司設計系統的 Cursor 規則與 design tokens，供新 POC 或專案套用。

---

## 內容

- **`.cursor/rules/`** — Cursor 規則（.mdc）
  - `company-design-system.mdc`：公司設計系統總則（tokens、Admin/Platform、Figma 流程）
  - `ux-writing.mdc`：UX writing（英文／日文介面文案）
  - `auto-push.mdc`：變更後自動 push（可依專案修改或關閉）
  - `README.md`：規則說明
- **`company-design-system/`** — Design tokens 與規範
  - `all-variables.css`：唯一 token 來源
  - `Claude-design-system-updates-2026-02-20.md`：元件規格與檢查表
  - `ux-writing.md`：UX writing 規則與必讀文件路徑
  - `README.md`：設計系統說明

---

## 在新 POC 或專案中套用

1. Clone 本 repo，或下載 `.cursor` 與 `company-design-system`。
2. 將 **`.cursor`** 與 **`company-design-system`** 複製到你的專案根目錄（與 `package.json` 或專案根同層）。
3. 在 Cursor 開啟該專案，製作 POC 或公司產品時啟用規則 **「company-design-system」**。
4. 在專案中引入 `company-design-system/all-variables.css`（路徑依專案調整）。
5. （可選）若不需要自動 push，可刪除或停用 `.cursor/rules/auto-push.mdc`，或修改其中的 push 路徑。

---

## 維護

規則與 tokens 更新後，可同步回本 repo，供其他專案或團隊成員使用。
