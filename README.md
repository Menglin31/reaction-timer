# reaction-timer

反應訓練用的方向箭頭計時器：全螢幕依序或隨機顯示 ↑ → ↓ ← 箭頭，適合搭配星狀伸展這類方向反應練習。

## 用法

打開 https://menglin31.github.io/reaction-timer/ ，設定後按「開始」。

| 設定 | 說明 |
|---|---|
| 順序 | 固定順序（↑ → ↓ ← 循環）或隨機 |
| 間隔（秒） | 每個箭頭出現的間隔，最短 1 秒 |
| 每組時間（秒） | 0 = 不限時間 |
| 開始前倒數（秒） | 預留站好位置的時間 |

執行中點螢幕即停止；練習時會保持螢幕常亮（需要瀏覽器支援 Wake Lock）。

## 檔案

| 檔案 | 說明 |
|---|---|
| `index.html` | 整個網頁（HTML + JavaScript），沒有其他依賴 |

## 部署

GitHub Pages：Settings → Pages → Source 選 `Deploy from a branch`，Branch 選 `main`、`/ (root)`。
