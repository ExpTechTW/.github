# ExpTech
<img alt="Discord" src="https://img.shields.io/discord/926545182407688273">

------

- 這是一個說明 目標 及 各項目狀態 的頁面

## 索引
- [文檔](#文檔)
- [目標概述](#目標概述)
- [開發中](#開發中)
- [日常維護、擱置項目](#日常維護擱置項目)
- [開發完成](#開發完成)
- [棄置項目、停止支援](#棄置項目停止支援)
- [貢獻者](#貢獻者)
- [發佈規則](#發佈規則)
- [合作](#合作)

## 文檔
- `開發中` 表示該項目仍持續推進進度
- `日常維護` 表示該項目不會頻繁推進進度 但依然可以使用
- `擱置項目` 表示該項目遇到問題 暫時不再有推進進度的計畫
- `開發完成` 表示該項目已經達到原始設計目標 不再主動推進進度
- `棄置項目` 表示該項目不再推進進度 但仍然可以使用 不過不保證穩定
- `停止支援` 表示該項目不再推進進度 且不再提供相關服務支援 ［如 API 服務器］

## 目標概述
- 建立 Websocket Server 在 Port 1015
- Esp32 OTA+Websocket 測試
- 線上答題網站
- RecordTree
- 學會如何使用 卡爾曼濾波 優化 MPU6050 的數據 `Rocket TVC固體火箭`
------

## 開發中
#### Answer
- 類型: `Web App`
- 概述: 課堂搶答網站
- 狀態: `開發中`
#### RecordTree
- 類型: `App (Android/iOS)`
- 概述: 一個用來記錄生活的社交軟體
- 狀態: `開發中`
#### API
- 類型: `Server`
- 概述: 為 ExpTech 提供服務的 API 服務器
- 狀態: `開發中`
#### Rocket TVC固體火箭
- 類型: `null`
- 概述: TVC火箭
- 狀態: `開發中`
------

## 日常維護、擱置項目
#### ExpTech_Core
- 類型: `Minecraft (Spigot)`
- 概述: Spigot 所有插件的核心
- 狀態: `日常維護`
#### Rocket TVC固體火箭
- 類型: `null`
- 概述: TVC火箭
- 狀態: `開發中`
#### ExpTech_DataRecord
- 類型: `Minecraft (Spigot)`
- 概述: 記錄伺服器中各項 統計數據 的插件
- 狀態: `日常維護`
#### ExpTech_Economy
- 類型: `Minecraft (Spigot)`
- 概述: 和 網頁 同步的 經濟 插件
- 狀態: `日常維護`
#### ExpTech_Website
- 類型: `Web`
- 概述: 經濟 插件的 網站 頁面
- 狀態: `日常維護`
#### ExpTech_DC_Bot 
- 類型: `Discord Bot`
- 概述: 對接 API 的 Discord Bot
- 狀態: `日常維護`
------
## 開發完成
#### ExpTech_Here
- 類型: `Minecraft (Spigot)`
- 概述: 顯示自身 位置訊息 的插件
- 狀態: `開發完成`
#### ExpTech_Organization
- 類型: `Minecraft (Spigot)`
- 概述: 讓伺服器擁有 組織 功能的插件
- 狀態: `開發完成`
#### ExpTech_BanSystem
- 類型: `Minecraft (Spigot)`
- 概述: 讓伺服器擁有 雲端防護 功能的插件
- 狀態: `開發完成`
#### ExpTech_FreeCamera
- 類型: `Minecraft (Spigot)`
- 概述: 讓玩家擁有 自由視角 功能的插件
- 狀態: `開發完成`
#### Spigot-PingTag
- 類型: `Minecraft (Spigot)`
- 概述: 在 Spigot 中顯示 Ping 的插件
- 狀態: `開發完成`
#### 天氣 Shi.Inc
- 類型: `App（Android）`
- 概述: 台南各區每小時天氣預報
- 狀態: `開發完成`
#### Music
- 類型: `App (Android/iOS)`
- 概述: YouTube MP3/MP4 檔案下載工具
- 狀態: `開發完成`
#### Count
- 類型: `App (Android/iOS)`
- 概述: 股票運算工具
- 狀態: `開發完成`
#### ExpTech
- 類型: `App (Android)`
- 概述: 擁有各式功能的 App
- 狀態: `開發完成`
#### Nukkit-Engineer
- 類型: `Minecraft (PowerNukkit)`
- 概述: 修復 PowerNukkit 中一些錯誤 的插件
- 狀態: `開發完成`
#### Nukkit-PingTag
- 類型: `Minecraft (PowerNukkit)`
- 概述: 在 PowerNukkit 中顯示 Ping 的插件
- 狀態: `開發完成`
#### Nukkit-ProhibitCommand
- 類型: `Minecraft (PowerNukkit)`
- 概述: 在 PowerNukkit 中禁止特定指令 的插件
- 狀態: `開發完成`
#### MCDR_LIST
- 類型: `Minecraft (Fabric_MCDR)`
- 概述: 在伺服器中顯示 所有玩家位置 的插件
- 狀態: `開發完成`
#### MCDR_Free_Camera
- 類型: `Minecraft (Fabric_MCDR)`
- 概述: 讓玩家擁有 自由視角 功能的插件
- 狀態: `開發完成`
-----

## 棄置項目、停止支援
#### SEVCS
- 類型: `Arduino`
- 概述: 時實計算 電動車 能耗並同步到 App
- 狀態: `棄置項目` `概念驗證用`
#### Spigot-Enginner
- 類型: `Minecraft (Spigot)`
- 概述: 修復 Geyser 中的一些問題
- 狀態: `棄置項目` `概念驗證用`
#### Discord-Bot-Public
- 類型: `Discord Bot`
- 概述: Discord Bot
- 狀態: `棄置項目` `維護困難`
#### Funlearn
- 類型: `App (Android/iOS)`
- 概述: 照片分享平台
- 狀態: `棄置項目` `維護困難`
#### 黑特灣中(行動版)
- 類型: `App (Android)`
- 概述: 粉專「黑特灣中」行動版
- 狀態: `棄置項目` `維護困難`
#### ExpTech
- 類型: `App (Android/iOS)`
- 概述: RecordTree 的前身
- 狀態: `棄置項目` `概念驗證用`
#### FSD
- 類型: `App (Android)`
- 概述: 仿比特幣區塊鏈數字貨幣交易工具
- 狀態: `棄置項目` `概念驗證用`
#### SFSP
- 類型: `App (Android)`
- 概述: 學生交流平台
- 狀態: `棄置項目` `概念尚未成熟`
#### 矽科技 | 智能設備
- 類型: `App (Android)`
- 概述: 矽科技設備控制工具
- 狀態: `棄置項目` `已由新版取代`
#### ExpTech_Discord_Bot
- 類型: `Discord Bot`
- 概述: 對接 API serverData 功能的 Discord Bot
- 狀態: `停止支援` `維護困難`
#### Nukkit-AntiCheat
- 類型: `Minecraft (PowerNukkit)`
- 概述: 在 PowerNukkit 中反作弊 的插件
- 狀態: `停止支援` `缺少依賴`
#### BDS-AntiCheat
- 類型: `Minecraft (Bedrock Dedicated Server)`
- 概述: 在 Bedrock Dedicated Server 中反作弊 的插件
- 狀態: `停止支援` `缺少依賴`
#### Discord-Economy-Bot
- 類型: `Discord Bot`
- 概述: 提供 經濟 玩法的 Discord Bot
- 狀態: `停止支援` `概念驗證用`
#### API-AntiCheat
- 類型: `Server`
- 概述: 為 Nukkit-AntiCheat 提供服務的 API
- 狀態: `停止支援` `概念驗證用`
#### dwhs_it
- 類型: `App (Android)`
- 概述: 各類破解軟體下載工具
- 狀態: `停止支援` `維護困難`
#### 在哪裡？ | 好友位置分享
- 類型: `App (Android)`
- 概述: 好友位置分享工具
- 狀態: `停止支援` `概念驗證用`
#### 天氣(舊)
- 類型: `App (Android)`
- 概述: 台南各區每小時天氣預報工具
- 狀態: `停止支援` `已由新版取代`
------

## 貢獻者
- whes1015 `文檔`

------

## 發佈規則
- 如果新版本中有錯誤，且尚未列出，請將錯誤資訊提交到 ```issue```
- 如果您使用任何形式的辱罵性或貶義性語言給其他用戶，您將永遠被封禁！
- 不要發送重複無意義內容至 ```issue```，否則您將永遠被封禁！
- 若有任何問題或建議，歡迎提出

## 合作
- 若有任何可以改進的地方，歡迎使用 ```Pull requests``` 來提交
