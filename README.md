# MingHao Kang（Larry）

**資深後端工程師 @ 一卡通（iPASS）**  
C#／.NET · 支付 API · 交易可靠性 · 系統整合 · AI 協作流程導入

自 2021/8 起從事正式後端開發，具 **5 年以上 C#／.NET 電子支付系統經驗**，另有製造業與專案管理背景。定居高雄，歡迎高雄或可長住高雄的 Remote／Hybrid 後端、系統整合與企業 AI 應用機會，可透過 [LinkedIn](https://www.linkedin.com/in/larry-kang/) 聯繫。

核心技術：**C#、.NET 8／.NET Core、ASP.NET Core Web API、MS SQL Server、Redis、Git**。

## 工作成果

- **支付 API 與可靠性**：設計 PayPay 正掃／反掃及公司 TWQR 交易流程，完成支付模組與外部服務整合、重複請求防護、非同步結果確認及 PayPay 狀態未明自動重問／補正。早期版本人工實作，現以 Agent 協作改版，仍由本人審核 C# 修改、驗收與正式環境排查。
- **流程模組化**：隨 TWQR 版本演進抽取共用付款與交易紀錄邏輯，支援自行／跨行、信用卡 3DS 與數位券等付款情境。
- **批次改善**：台水待繳帳單排程由逐筆查詢改為批次 API，依執行紀錄量測，執行時間縮短約 **90%**；另負責大樓管理費服務開發及票交既有功能擴充。

## Agent 協作與團隊導入

- 作為跨單位 FDE 小組兩位 RD 代表之一，**獨立建立 RD 共用 Skill、使用規範與 CI 格式驗證**。2026/8 完成主管審查、首版發布與全組教學，已有部分同事開始使用，採用仍處初期。
- 以 Agent 協作完成數個「需求 → Spec → 開發 → 驗收 → PR／異動單」工作任務；本人審核計畫、C# 修改及驗收結果，交付草稿經人工確認後執行。
- 參與 AI 協作的 Python／FastMCP **Beta POC**，負責需求、規格與功能驗證，完整 Agent 流程待分工整合。

日常使用 Codex、GitHub Copilot。Python、FastAPI、FastMCP、Docker、GitHub Actions 與 MCP 串接屬 AI 協作原型／工具接觸，實作主要由 AI 完成。

## 公開作品

| 作品 | 成果與狀態 | 本人貢獻 |
| --- | --- | --- |
| [PetPet.Modern](https://github.com/Larry-kang/PetPet/tree/master/PetPet.Modern) |  .NET 8 寵物社群本地 Demo：EF Core、SQLite、SignalR；一鍵啟動、120 位合成會員、1,200 則貼文與 2,400 則留言；72 項自動化測試及瀏覽器／本人操作驗收，未對外營運 | 原版手寫；Modern 程式主要由 Agent 協作改造，本人主導需求、規格與成果驗收 |
| [GAS_Asset_Tracker](https://github.com/Larry-kang/GAS_Asset_Tracker) | 個人資料整合工具：每日快照、每 30 分鐘價格同步 | 初版以 GAS 手寫；後續 AI 協作，本人負責需求與驗收 |
| [market-regime-weekly](https://github.com/Larry-kang/market-regime-weekly) | 公開市場資料、日報／週報與網站發布 | 本人提出需求、確認規格及查看結果；程式由 AI 產生 |
| [TWQR-Transaction-Core](https://github.com/Larry-kang/TWQR-Transaction-Core) | 個人支付早期 POC，部分目標仍在規劃；與公司正式系統分開呈現 | 公開框架由 AI 建立，本人討論需求與規格 |

[查看公開市場報告](https://larry-kang.github.io/market-regime-weekly/)

公開作品以一般技術與公開資料為範圍，不展示公司內部程式碼、規格、交易資料或個人帳號、憑證與資產現況。
