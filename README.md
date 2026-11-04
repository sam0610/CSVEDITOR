# CSV 修改器

<img src="icon-192.png" width="96" alt="CSV 修改器圖示">

手機用的單檔網頁,開啟 CSV、直接在格內輸入、加減列欄、尋找取代、復原,再匯出成 CSV。沒有後端,資料只留在自己的瀏覽器。

## 使用

- 用 GitHub Pages 發佈後,在手機 Safari 開啟網址,再選「加入主畫面」就像一個 App(會用琥珀色逗號圖示)。
- 也可以直接用瀏覽器開啟 `index.html`。

## 功能

- 一開頁面先揀「新增」(5 × 5 空白表格)或「開啟」(選擇 CSV 檔案),冇範例資料。
- 表格最尾一欄、最尾一列有 `+`,一按就加欄或加列。
- 開啟 CSV:自動偵測 UTF-8 或 Big5,亂碼時可手動改編碼(Big5、GB18030)。
- 點格直接輸入,Enter 跳到下一列,箭頭掣跳到隔籬格。
- 刪列、刪欄、首列當標題、尋找取代、復原重做。
- 匯出時可揀檔名、分隔符號(逗號、分號、Tab)和是否加入 BOM。
- 編輯中、未匯出的內容會暫存在瀏覽器,重開頁面會還原。

## 檔案

- `index.html`:整個 App(單檔)
- `favicon.svg`、`apple-touch-icon.png`、`icon-192.png`、`icon-512.png`、`manifest.webmanifest`:圖示與加入主畫面設定

## 發佈到 GitHub Pages

Settings → Pages → Branch 選 `main`,資料夾選 `/ (root)`。免費帳戶需要 public repo。
