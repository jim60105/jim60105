### 🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜

我是來自**台灣**的程式設計師，目前正在大台北地區尋找**C#研發工作**，偏好**網頁後端研發**\
我個人有兩年的Unity遊戲外掛開發經驗，對C#操作有一定基礎\
(我專注在C#撰寫，沒有點美術和遊戲開發技能樹)

近二十個外掛作品中，最複雜的當屬[服裝卡選擇性載入插件](https://github.com/jim60105/KK/tree/master/KK_CoordinateLoadOption)
> 琳的備忘手札 - [Koikatu][BepInEx v5.X] 服裝卡選擇性載入插件 (Coordinate Load Option)\
> https://blog.maki0419.com/2019/03/koikatu-coordinate-load-option.html

在該遊戲的原始設計中，服裝存檔一次只能讀入一整套，並且其它的插件也是如此設計\
為了實現部份讀取，我只能在外部拆分其它各插件的數據\
我堅持不列不必要依賴，取而代之用了大量的reflection操作，以達到最大兼容性 (相對的，可維護性很糟。嘛，練手作品)\
反組譯出來的code沒有註解，為了尋找注入點、與程式交互，這很鍛鍊程式邏輯\
這些過程讓我學到很多

這裡有一份我自己撰寫的[Reflection工具箱](https://github.com/jim60105/KK/blob/ed1d022e33adfa99114d67d6792f6df3e6d7427b/Extension/Extension.cs#L18)，作為技術參考

---
*在此附上我的Koikatu遊戲外掛作品頁*

> 琳的備忘手札 - [Koikatu] コイカツ！ ( Koikatu / Koikatsu / 戀愛活動 ) 個人插件介紹匯整\
> https://blog.maki0419.com/2020/05/personal-koikatu-plugin.html
---

另外，我也有JavaScript開發經驗。我的畢業專題主要使用Angular開發，也寫過不少[有的沒的網站](https://github.com/jim60105?tab=repositories&q=&type=&language=javascript)
> Github - jim60105/PMS5003TAirQuality 樹莓派空氣汙染監測系統之實作\
> https://github.com/jim60105/PMS5003TAirQuality

比較近期的前端作品有: [Youtube影片截選播放佇列](https://blog.maki0419.com/2020/10/userscript-youtube-end-param-handler.html)、[三向語言標籤](https://gist.github.com/jim60105/d7aaa9c25e7cdb4098e591115633cd6f)、[Blogger的自動TOC](https://gist.github.com/jim60105/2d892ca5d898397e5e52f127cc84b129)、[Blog右下角的抖內彈窗](https://gist.github.com/jim60105/b38a23e9a69ad81bd1059fda87530a78) 等\
雖然我對js並不專精，但**我對網頁開發整體有充分的概念，有信心能和前端工程師良好配合**
> 琳的備忘手札 - [UserScript] Youtube影片截選播放佇列 (Youtube End Param Handler)\
> https://blog.maki0419.com/2020/10/userscript-youtube-end-param-handler.html

---
### 其它亂點的技能樹
我為了host網站，2014年從網樂通起頭，至樹苺派、香蕉派架站，而現在長期在DigitalOcean租主機\
由當時入門Arch Linux至今，能說我對於**網域購買設定、主機架設、Linux指令**都有一定經驗
> 琳的備忘手札 - [開箱] Banana Pi 香蕉派M3 各種體驗感想\
> https://blog.maki0419.com/2016/03/banana-pi-m3.html

> 琳的備忘手札 - Bananapi 香蕉派M3 Cross Compile 教學\
> https://blog.maki0419.com/2016/03/bananapi-m3-cross-compile.html

今年的待業期間，我粗淺的自學了**Docker技術**，有簡單的docker-compose file作品\
像是我的個人空間NextCloud，用做Koikatu插件發佈；另外還有Opencart和V2Ray，這些服務現在都在我的主機上運行
> 琳的備忘手札 - [Docker] Nextcloud自有雲建置\
> https://blog.maki0419.com/2020/07/docker-nextcloud.html

> 琳的備忘手札 - [Docker] Opencart購物網站建置\
> https://blog.maki0419.com/2020/08/docker-opencart.html

> Github - jim60105/docker-V2Ray V2Ray on Docker\
> https://github.com/jim60105/docker-V2Ray

我最近還弄了個Youtube錄影伺服器\
原本只是想做dockerize方便部屬，沒想到為了解bug和加新功能而把整個專案view了一次\
而且這還是我不懂寫的Bash和Python，很努力才能改動
> 琳的備忘手札 - [Docker] Youtube直播錄影伺服器建置\
> https://blog.maki0419.com/2020/11/docker-youtube-dl-auto-recording-live-dl.html

基於興趣，**Arduino**創作也稍有接觸，家裡有不少奇怪的開發板和週邊
> Github - jim60105/BluetoothRemoteCar 藍芽搖控小車\
> https://github.com/jim60105/BluetoothRemoteCar
 
台灣著名的LASS環境感測專案我也參了一腳，為之寫了**Android App和Domoticz Plugin**\
Android App上架在GooglePlay，介面簡單但功能明確\
Domoticz是一個Home automation系統，我以Python寫了一個串接LASS資料的外掛
> 琳的備忘手札 - [Android App] PM2.5 環境空氣顯示器 ( Airbox 、 LASS 等民間Maker站點 )\
> https://blog.maki0419.com/2019/01/android-app-pm25-airbox-lass.html

> Dropbox Paper - Domoticz Python Plugin for LASS\
> https://tinyurl.com/y56p4r7e

我大學時研究過把GoogleSheet做為Database使用，並確實做出了[實現](https://figure-database.maki0419.com/)
> 琳的備忘手札 - 以Google試算表作為簡易資料庫(上)--資料庫的建立及寫入\
> https://blog.maki0419.com/2015/06/google-database.html

甚至，那時我曾在家擁有一台[3D印表機](https://www.facebook.com/jim60105/videos/1077958822223728/)，學過[Solidworks制圖](https://www.facebook.com/photo.php?fbid=1077212975631646&set=a.218403838179235&type=3)\
當時還接case做機械制圖，賺些零用錢花

興趣玩得很多很雜，不過真的很開心

### 🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜
歡迎透過以下方式聯絡:
* Blogger https://blog.maki0419.com/
* Email jim60105@gmail.com
* Facebook https://www.facebook.com/jim60105
### 🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜🦜
