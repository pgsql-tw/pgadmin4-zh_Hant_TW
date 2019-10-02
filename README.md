# pgadmin4-zh_Hant_TW
pgAdmin 4 的台灣中文介面
- 最新測試版本: 4.13
- 版本不同仍然可用，對不上的詞句會以英文顯示。

## 注意
- 本專案目前為初始狀態，大多由簡體中文轉為正體中文，再逐條重寫。
- 歡迎協作，請提供更親切的台灣用語。
- 語言檔編譯請參考 [pgAdmin 官方手冊](https://www.pgadmin.org/docs/pgadmin4/development/translations.html)
- 或直接開 issue 反映，再由社群人員協助編譯。

## 第一次使用
1. 下載本專案，並且找到你的 pgAdmin4 安裝路徑。
2. 把 web 目錄貼到你的 pgadmin4 下的 web。（都是新檔案，不用擔心）。
3. 依 web/config-update-lanague.py 修改你的 web/config.py，加入"Mandarin (Taiwan)"，不要直接覆蓋！
4. 打開 pgAdmin4，設定 User Language，選擇 Mandarin，Reset Layout。
5. 有時候會需要重新啓動 pgAdmin4 的服務才能清除快取。

## 後續更新
- 下載 [messages.mo](web/pgadmin/translations/zh_Hant_TW/LC_MESSAGES/messages.mo) 去覆蓋原檔即可。

---
[![](https://img.shields.io/badge/台灣使用者社群-PostgreSQL-blue.svg)](https://postgresql.tw)
