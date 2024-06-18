---
title: 六角學院體驗營 Week2
date: 2024-05-05 14:42:39
tags:
    - 程式紀錄
---
本週主題重點：講解 Flex 最常使用的六大語法，Flexbox 多欄式排版的應用。以下是一些自己的筆記和心得~
## 本週課程的重點語法
* **display: flex**
* **flex-direction**
    * 決定 flex 的軸線
    * 可以根據使用者習慣的資訊流使用 reverse

* **justify-content**
    * 主軸對齊

* **flex-wrap** 
    * 換行設定
    * 當子元素(們)寬度超過父層時，flex 預設會自適應寬度，可以用 wrap 來實現換行

* **align-items**
    * 交錯軸單行對齊
    * 相對於主軸的另一個軸線，所以要先確定自己的主軸是哪個方向

* **align-content**
    * 交錯軸多行對齊
    * 就簡單的理解上來說，比較是當 flex 出現 wrap 時會發生
    * 跟 align-items 都是交錯軸的對齊方式
    * 補充：[align-content 屬性介紹](https://w3c.hexschool.com/flexbox/d0e569ef)、[align-items與align-content比較](https://guiblogs.com/flex-align/)

* **Flex 裡還可以包 Flex**
    * 父層的設定 flex 只會影響子層
    * 子層裡面可以繼續有 flex

![flex css](https://hackmd.io/_uploads/rySBtzcfR.png)

>圖片來源：[CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-flex-direction)