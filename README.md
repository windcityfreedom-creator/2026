# 新竹市公共事務資料整理 — GitHub Pages

純靜態网站；不需要Cloudflare、後端、安裝套件或自訂GitHub Actions。

## 發布步驟

1. 將本資料夾的內容放入新的專用GitHub儲存庫，保留docs資料夾結構及docs/.nojekyll。
2. 在Settings → Pages選Deploy from a branch。
3. Branch選main（或實際主要分支），資料夾選/docs，按Save。
4. 以Pages提供的網址查看結果；更新docs內公開檔案再推送即可更新網站。

網站網址會包含GitHub帳號與儲存庫名稱。GitHub Free的Pages需公開儲存庫；Pro等方案可從私人儲存庫發布，網站仍可能公開。若避免連結個人身分，使用專用帳號，第一次提交前設定專案化名及專用或noreply作者／提交者信箱。Git平台仍可能保有帳號及連線資料。

## 網站內容與限制

議員34位、市長38項主要計畫；所有HTML、CSS與JavaScript均在docs。原始PDF使用公開來源外連，沒有工作日誌、原始腳本、截圖或本機路徑。

頁面使用相對連結，可在帶儲存庫路徑的專案網站運作。最大的HTML約20.16 MiB，行動網路初載可能較慢。

Cloudflare的_headers不適用GitHub Pages，已排除。頁面仍保留no-referrer設定，沒有加入追蹤碼；沒有宣稱GitHub Pages會套用Cloudflare的CSP、拒絕嵌入等安全標頭。

僅把HTML放進Git儲存庫不會自動變成網站，需另外啟用Pages。本包尚未上傳或部署。

[GitHub Pages介紹](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)
[發布來源設定](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
