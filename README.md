# endfield-dictionary

《明日方舟：終末地》遊戲相關素材與數據映射字典 (Mapping Dictionary)。本資料庫主要功能為「Endfield Gacha Tracker (終末地尋訪紀錄終端)」 的輔助工具，作為外部數據解析與圖像顯示的靜態依賴來源。

---

## 資料結構與來源說明

本專案目前包含以下三個核心的 JSON 映射檔案：

* **`avatar_mapping.json`**：收錄遊戲內角色名稱與其官方頭像圖片網址的對應關係。圖片資源取自 [官方網站角色介紹頁面](https://endfield.gryphline.com/zh-tw/operator)。
* **`weapon_mapping.json`**：收錄遊戲內武器名稱與其圖片網址的對應關係。圖片資源取自 [森空島 Wiki (武器圖鑑)](https://wiki.skland.com/endfield/catalog?mainTypeId=1&subTypeId=2&header=0)。
* **`banner_up_mapping.json`**：收錄各尋訪卡池名稱與其對應的 UP 角色或武器陣容。資訊來源彙整自 [森空島 Wiki (角色卡池)](https://wiki.skland.com/endfield/detail?mainTypeId=1&subTypeId=1&gameEntryId=1676&header=0) 與 [森空島 Wiki (武器卡池)](https://wiki.skland.com/endfield/detail?mainTypeId=1&subTypeId=2&gameEntryId=1681&header=0)。

---

## 免責聲明與版權限制

1. **遊戲素材版權**：本倉庫內所整理與連結之所有角色圖像、武器圖片、專有名詞與遊戲資訊，其版權均嚴格歸屬於《明日方舟：終末地》官方發行商所有。
2. **非商業用途限制**：本專案僅作為開源社群交流、程式開發練習與玩家個人輔助工具之資料索引使用。嚴禁任何人提取本倉庫內的連結與資源，進行任何形式的商業營利或未經授權之散布行為。
3. **資料有效性**：本專案內儲存之圖片連結皆為官方或官方合作之外部網址。若未來來源端更改網址結構或刪除圖片，開發者不保證連結的永久有效性。
