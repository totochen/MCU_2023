---
layout: post
title: Innovative Project Proposal
author: [Toto Chen]
category: [Lecture]
tags: [jekyll, ai]
---

This homework is to specify a INnovative Project Proposal and describe the key features, list all Design Considerations and the required technologies, then draw the System Block Diagram.

---
## Futre Home Applications

### 智能冰箱

<iframe width="950" height="550" src="https://www.youtube.com/embed/dE3B0W-H4JQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---
## 智能冰箱
### 應用功能說明
1. 食物倉儲：冰箱也是家中食物的倉庫。利用影像辨識存放或取出冰箱的食物，<br>含種類、數量、到期日等資料，可以隨時查詢冰箱中還有那些食物。
2. 即期食品通知：對於即將到期的食品，發出提醒訊息。
3. 食物腐敗偵測：利用氣體偵測感應器，偵測冰箱中是否有食物過期且散發腐敗氣體。 
4. 安全防護：利用人臉偵測, 拒絕小小孩自己打開冰箱，可避免小小孩關到冰箱中，或是取物時，物品掉落。
5. 提醒食量：利用人臉偵測, 記錄家中成員每天開冰箱的次數，以及拿取那些東西，<br>如果成員中有需要控制食量或是食物種類時，會提醒成員當天是否已經吃過或是已達食量上限。
6. 依家庭喜好，推薦食譜：依照冰箱的內存物, 給予建議食譜, 透過家庭喜好, 修正推薦的食譜。

### 設計考量與相關技術
**系統設計考量：**<br>
1. 供電方式:電池＋自動充電
2. 聯網方式: WiFi 或 BLE to中控電腦

**所需相關技術：**
1. 主體運行與控制: ESP32
2. 氣體偵測(偵測水蒸氣裡有食物腐敗產生的水溶性氣體，如氨、三甲胺、二氧化碳等):<br> MQ137、NH3、SGP30、AM2302
3. 人臉辨識: ESP32-CAM模組
4. 食物辨識: Jetson Nano、NodeMCU-32S、PCA9685、IMX219
5. 網路服務及資料庫: 透過WIFI上傳食物資料至MySQL
6. 喜好推薦: 使用Php 程式設計, 記錄家庭成員行為, 學習成員喜好, 給予推薦

### 系統方塊圖
![](https://github.com/totochen/MCU_2023/blob/master/images/system_block.jpg?raw=true)



<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*


