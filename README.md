# Star Archive

從 GitHub star 清單中封存的專案，共 **440** 個。這些專案已停止維護（封存、標示棄用，或超過兩年無 push），已從主 star 清單移除，記錄保留於此。

封存日期：2026-09-05　｜　原始 star 總數：2270　｜　保留仍活躍者：1830

判斷標準：`archived=true`、描述含棄用字樣、或 `pushed_at` 超過 24 個月。學習資源與內容型專案（awesome list、教學、筆記）不列入封存，因為停更不影響其價值。

## 分類索引

| 分類 | 數量 | 已封存 | 停更 >3年 |
|---|---:|---:|---:|
| [前端 / UI](archive/frontend-ui.md) | 102 | 18 | 59 |
| [其他 / 未分類](archive/misc.md) | 81 | 19 | 34 |
| [AI / LLM / Agent](archive/ai-llm-agent.md) | 65 | 23 | 8 |
| [後端 / API / 框架](archive/backend-api.md) | 62 | 12 | 43 |
| [開發工具 / CLI](archive/devtools-cli.md) | 30 | 8 | 19 |
| [桌面 / 行動 App](archive/desktop-mobile.md) | 29 | 8 | 15 |
| [資料處理 / 爬蟲](archive/data-scraping.md) | 21 | 3 | 15 |
| [媒體 / 影音處理](archive/media.md) | 19 | 1 | 6 |
| [機器學習 / 資料科學](archive/machine-learning.md) | 14 | 2 | 6 |
| [自架服務 / DevOps](archive/selfhosted-devops.md) | 10 | 4 | 8 |
| [遊戲開發](archive/gamedev.md) | 5 | 2 | 3 |
| [安全 / 隱私](archive/security.md) | 2 | 0 | 1 |
|  |  |  |  |
| **總計** | **440** | **100** | **217** |

## 資料檔

- [`data/archived.tsv`](data/archived.tsv) — 本次封存清單，含原始加星日期
- [`data/stars-full.tsv`](data/stars-full.tsv) — 完整 2270 筆原始匯出

## 還原

`data/archived.tsv` 保留了每個專案的原始 `starred_at`。若要重新 star，可用 `PUT /user/starred/{owner}/{repo}`，但 GitHub 會將加星日期記為當下，原始日期僅存於此檔案。
