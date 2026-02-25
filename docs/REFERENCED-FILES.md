# 參考檔案清單 — 上傳 GitHub 與路徑更新

本文件列出專案內**所有被參考的檔案／資料夾**。  
**UX writing 與 Example 已收錄於 `docs/`**，路徑已更新為專案相對路徑，clone 後即可使用。

---

## 一、目前參考路徑總覽

### 1. UX Writing 必讀文件（已收錄於 `docs/ux-writing/`）

| 語系 | 路徑（專案內） |
|------|----------------|
| **英文** | `docs/ux-writing/English/UX Writing Guideline/`（主文件、CSV、image.png） |
| **日文** | `docs/ux-writing/日本語/UXライティングガイドライン/`（主文件、CSV） |
| **日文** | `docs/ux-writing/日本語/用語索引/`（主文件、CSV） |

**說明**：`ux-writing.md` 已改為參照以上路徑，無需本機絕對路徑。

---

### 2. Platform／Learner 設計範例（已收錄於 `docs/design-examples/`）

| 類型 | 路徑（專案內） |
|------|----------------|
| Platform 範例 | `docs/design-examples/Platform example/`（登入、Sidebar、Drawer、表格、Dialog 等 PNG） |
| Learner 範例 | `docs/design-examples/Learner example/` |

**說明**：`company-design-system.mdc` 與 `company-design-system/README.md` 已改為參照以上路徑。

---

### 3. 專案內檔案（已在 repo 內，無需從本機再上傳）

| 用途 | 路徑（專案內相對路徑） |
|------|------------------------|
| Design tokens | `.cursor/company-design-system/all-variables.css` |
| 規格與檢查表 | `.cursor/company-design-system/Claude-design-system-updates-2026-02-20.md` |
| UX writing 規則 | `.cursor/company-design-system/ux-writing.md` |
| 設計系統說明 | `.cursor/company-design-system/README.md` |
| Cursor 規則 | `.cursor/rules/company-design-system.mdc`、`.cursor/rules/auto-push.mdc` 等 |

---

### 4. 其他參考（路徑待依環境更新）

| 檔案 | 參考內容 | 說明 |
|------|----------|------|
| `.cursor/rules/auto-push.mdc` | `cd /Users/liang/Documents/my-first-rpg && ./push.sh` | 專案專用，上傳後可改為新 repo 路徑或關閉。 |

---

## 二、建議 GitHub repo 結構（上傳後可改的路徑）

上傳後可將「外部路徑」改為 repo 內相對路徑，例如：

```
your-repo/
├── .cursor/
│   ├── company-design-system/
│   │   ├── ux-writing.md      ← 更新內文路徑指向 docs/ux-writing/...
│   │   └── ...
│   └── rules/
│       └── company-design-system.mdc  ← 更新 Platform 範例路徑
├── docs/
│   └── ux-writing/
│       ├── en/                 ← 放「Platform UX Writing Guideline」整包
│       │   └── Platform UX Writing Guideline 22673b65c91481778eaaec2abead2c1c.md
│       └── ja/                 ← 放「Platform UXライティングガイドライン」+「用語索引」整包
│           ├── Platform UXライティングガイドライン 22673b65c9148038a403e9c5e352b42f.md
│           └── 用語索引 22673b65c91480418e22ed5dc6381255.md
├── design-examples/            ← 或 design-files/
│   └── Platform/              ← 放 company-design-system/examples/Platform 內容
└── REFERENCED-FILES.md        ← 本清單（可放在 docs/ 或根目錄）
```

---

## 三、上傳後要更新路徑的檔案

| 檔案 | 要改的內容 |
|------|------------|
| **`.cursor/company-design-system/ux-writing.md`** | 將「二、英文」與「三、日文」表格中的絕對路徑改為 `docs/ux-writing/en/`、`docs/ux-writing/ja/` 等相對路徑（或你實際放置的位置）。 |
| **`.cursor/rules/company-design-system.mdc`** | 「五、參考資源路徑」表中 Platform 範例改為 `design-examples/Platform` 或 `docs/design-examples/Platform`。 |
| **`.cursor/company-design-system/README.md`** | Platform 範例路徑改為 repo 內相對路徑。 |
| **`.cursor/rules/auto-push.mdc`** | 若保留自動 push，將 `my-first-rpg` 路徑改為本 repo 路徑或改為「依專案修改」。 |

---

## 四、檢查清單（上傳前）

- [ ] 已複製「Platform UX Writing Guideline」整包（含主文件與同資料夾檔案）到可上傳的目錄
- [ ] 已複製「Platform UXライティングガイドライン」整包
- [ ] 已複製「用語索引」整包
- [ ] 已複製「company-design-system/examples/Platform」到可上傳的目錄
- [ ] 決定 repo 內放置路徑（如 `docs/ux-writing/`、`design-examples/Platform`）
- [ ] 上傳後依「三、上傳後要更新路徑的檔案」修改並 commit

---

*本清單由專案內參考掃描產生，路徑為撰寫時之本機絕對路徑，上傳 GitHub 後請依實際結構更新。*
