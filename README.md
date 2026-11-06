# 高雄 Rang 阿米吃桌

BTS 粉絲自發活動的桌次查詢前端。

1. 將此資料夾內容上傳至 rang-table/rang-table.github.io 的 main 分支。
2. GitHub 儲存庫 Settings → Pages → Deploy from a branch → main / (root) → Save。
3. 完成 Cloudflare API 部署後，修改 config.js 的 apiBaseUrl，填入實際 HTTPS 網址，結尾不加斜線。
4. 等待 Pages 部署成功，再用手機開啟 https://rang-table.github.io/ 測試。

API 尚未設定時，頁面會提示查詢尚未開放，不會送出來賓輸入。不可把真實名單、API token 或 Cloudflare 金鑰放進這個公開儲存庫。API 的公開網址可以放在 config.js，它不是金鑰。

目前採本名＋轉帳後五碼查詢；尚未改成個人報到碼，也不會記錄報到狀態。
