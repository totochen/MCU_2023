---
layout: post
title: 溫溼度感應器(Temperature and Humidity Sensor)
author: [Toto Chen]
category: [Lecture]
tags: [Temperature Sensor, Humidity Sensor, IoT]
---

This homework is to specify a temperature and humidity sensor, list all Design Considerations and the required technologies, then draw the System Block Diagram.

---

# 濕度感應器 (Tempature and Humidity Sensor)

## 影片展示 : 溫濕度感應器 (Tempature and Humidity Sensor)
### 說明：展示溫溼度感測器將偵測到的溫溼度，透過client端，上傳至server端。利用手機查看遠端環境的溫溼度

<div align="center">
<iframe width="640" height="360" src="https://www.youtube.com/embed/LnylPsm3WLg?autoplay=1&loop=1" title="HTU21 Sensor Load" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

</div>

### 說明：溫溼度感測器每隔一段時間，會自動將偵測到的溫溼度，透過client端，上傳至server端。利用手機可以重整頁面資料，查看即時遠端環境的溫溼度

<div align="center">
<iframe width="640" height="360" src="https://www.youtube.com/embed/iD3TQeTwKZs?autoplay=1&loop=1" title="HTU21 Sensor Reload" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

</div>

---

## 功能說明
**1. 偵測周遭環境的溫溼度感應器** <br>
**2. 溫溼度偵測結果，定時由Client端上傳至Server端。**<br>
**3. 透過手機可以看到即時遠端的溫溼度** <br>


## 系統設計：
### 1. 電路設計：利用ESP32來設計溫溼度感測器的電路設計，電路圖如下：
![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ3_circuit.png?raw=true)

### 2. 系統架構圖
![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ3_System_Arch.png?raw=true)


### 3. DHT22 溫溼度感測器
### 開始測試前
![](https://github.com/totochen/MCU_2023/blob/master/images/DHT22_Sensor_Initial.png?raw=true)

### 接收到溫溼度感測結果
![](https://github.com/totochen/MCU_2023/blob/master/images/DHT22_Sensor_Value.png?raw=true)

### 4. HTU21 數位微型溫濕度感測器
### 接收到溫溼度感測結果
![](https://github.com/totochen/MCU_2023/blob/master/images/HTU21_Sensor_Value.png?raw=true)


### 4. 程式設計： 




<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*

