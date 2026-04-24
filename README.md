# OpenSpec 介紹頁面 · 正體中文使用說明

OpenSpec 規格驅動開發框架的靜態介紹頁面，以及完整的正體中文使用說明文件。

---

## 檔案結構

```
.
├── index.html              # 介紹頁面（靜態 HTML，可直接用瀏覽器開啟）
├── style.css               # 頁面樣式（Mistral.ai 暖色調設計系統）
├── OpenSpec_使用說明.md    # OpenSpec 完整正體中文使用說明（v1.2.0）
├── DESIGN.md               # 設計系統規範（基於 Mistral.ai 視覺語言）
└── openspec/               # OpenSpec 規格文件目錄（本專案自身使用）
```

---

## 本地預覽

直接雙擊 `index.html` 在部分瀏覽器（Chrome）會因安全限制而無法載入外部 CSS，建議使用本地 HTTP server：

```bash
# 方式一：npx（無需安裝，推薦）
npx serve .

# 方式二：Python
python3 -m http.server 8080
```

啟動後開啟：`http://localhost:3000`（serve）或 `http://localhost:8080`（Python）

---

## 介紹頁面內容

`index.html` 依序包含以下區塊：

| 區塊 | 說明 |
|------|------|
| Navigation | 品牌導覽列，含錨點連結與 GitHub 按鈕 |
| Hero | 大型標題、統計數據、安裝指令、CTA 按鈕 |
| Features | 4 張功能卡片（規格文件層、AI 整合、迭代工作流程、Brownfield 適用） |
| Commands | 核心 4 個 + 擴展 7 個 OPSX 斜線命令說明 |
| Workflow | 三步驟流程（Propose → Apply → Archive）示範 |
| Comparison | OpenSpec vs Spec Kit vs Kiro 比較表 |
| Footer | 官方資源連結與版權資訊 |

---

## 關於 OpenSpec

OpenSpec 是專為 AI 程式碼助理設計的**規格驅動開發（Spec-Driven Development）**框架，讓你在動手寫程式前先和 AI 建立共識。

- **GitHub**：[Fission-AI/OpenSpec](https://github.com/Fission-AI/OpenSpec)
- **官方網站**：[openspec.dev](https://openspec.dev)
- **npm 套件**：[@fission-ai/openspec](https://www.npmjs.com/package/@fission-ai/openspec)
- **Discord 社群**：[discord.gg/YctCnvvshC](https://discord.gg/YctCnvvshC)
- **完整說明文件**：見本倉庫 [OpenSpec_使用說明.md](./OpenSpec_使用說明.md)

---

> 根據 OpenSpec v1.2.0 官方資料整理 · MIT License
