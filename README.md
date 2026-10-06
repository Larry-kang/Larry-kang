# Larry Kang

**資深後端工程師 Senior Backend Engineer @ 一卡通（iPASS）**  
C# / .NET · 支付 API · 系統整合 · 交易可靠性 · Agent 協作

自 2021/8 起從事正式後端開發，具 **5 年以上 C#／.NET 電子支付系統經驗**。結合職涯前期的製造業與專案管理背景，習慣從需求釐清、規格與工作拆解，推進到實作、驗收與跨部門交付。

定居高雄，歡迎高雄或可長住高雄的 **Remote／Hybrid 資深後端、系統整合與企業 AI 應用職缺**，可透過 [LinkedIn](https://www.linkedin.com/in/larry-kang/) 聯繫。

## 正式工作實績

- **支付 API 設計與系統整合**：設計 PayPay 正掃／反掃與公司 TWQR API 流程，整合支付模組及外部服務，處理交易狀態、冪等性與非同步結果確認；TWQR 隨版本演進抽取共用支付及交易紀錄邏輯，支援跨行、信用卡 3DS 與數位券等情境。
- **資料處理與批次改善**：台水待繳帳單排程由逐筆查詢改用批次 API，依執行紀錄量測，執行時間縮短約 **90%**。
- **C# 開發與正式環境排查**：早期支付版本人工實作，現以 Agent 協作持續改版；本人仍負責 C# diff 審查、修改邏輯確認、驗收與正式環境異常排查。

核心技術：**C#、.NET 8／.NET Core、ASP.NET Core Web API、MS SQL Server、Redis、Git**。

## Agent 協作與團隊導入

- 已在數個實際工作任務完成「需求 → Spec → 開發 → 驗收 → PR／異動單」。Agent 建立計畫、文件及交付草稿，本人審核規格、C# 修改與驗收結果；commit／PR／異動單經人工確認後執行。
- 為公司跨單位 FDE 小組的兩位 RD 代表之一，**獨立建立 RD 共用 Skill、使用規範與 CI 格式驗證**。首版於 2026/8 經組長及主管 review 後發布，完成全組教學；部分同事已開始使用，目前為初期採用。逐月收集領域知識、review 後進版為後續規劃。
- 協助跨單位 **Python／FastMCP Beta POC**，以 AI 協作串接既有 API 與測試環境後台。部分功能已有驗證，完整 Agent 流程待分工整合；本人負責需求、規格與驗證結果確認。

日常使用 Codex、GitHub Copilot。新技術原型主要由 AI 產生程式，本人以需求、規格討論與結果驗證為主；Python、FastAPI、FastMCP、Docker、GitHub Actions 與 MCP 串接屬 AI 協作接觸／原型經驗，核心可獨立維護的專長仍以 C#／.NET 後端為主。

## 公開作品與本人貢獻

| 作品 | 定位與本人貢獻 |
| --- | --- |
| [TWQR-Transaction-Core](https://github.com/Larry-kang/TWQR-Transaction-Core) | 個人支付系統早期 POC，公開框架由 AI 協作建立；本人透過需求與規格討論探索支付工程議題。部分目標仍在規劃，完成範圍以程式碼與測試為準，與公司正式 TWQR 系統分開呈現。 |
| [PetPet.Modern](https://github.com/Larry-kang/PetPet/tree/master/PetPet.Modern) | 原始 PetPet 為轉職職訓期間手寫作品；Modern 為後續 Agent 協作的 .NET 8 改造，呈現既有系統整理與重構成果。 |
| [GAS_Asset_Tracker](https://github.com/Larry-kang/GAS_Asset_Tracker) | 初版本人以 Google Apps Script 撰寫，後續主要由 AI 協作改版，本人負責需求與結果驗收。個人使用工具，具每日排程快照及每 30 分鐘價格同步。 |
| [market-regime-weekly](https://github.com/Larry-kang/market-regime-weekly) | 公開市場資料與日報／週報專案，程式由 AI 產生；本人提出需求、確認規格與驗證結果。以 Python、GitHub Actions 與 GitHub Pages 進行資料更新及報告發布。 |

[公開市場報告網站](https://larry-kang.github.io/market-regime-weekly/)

公開作品僅呈現一般技術與公開資料，不包含公司內部程式碼、規格、交易資料，亦不展示個人帳號、憑證或資產現況。
