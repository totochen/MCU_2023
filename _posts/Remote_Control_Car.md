---
layout: post
title: Remote Control Car
author: [Toto Chen]
category: [Lecture]
tags: [Remote Control, Arduino, App Inventer2, Application]
---

This homework is to specify a INnovative Project Proposal and describe the key features, list all Design Considerations and the required technologies, then draw the System Block Diagram.

---
## Remote Control Car

### 遙控車

<video width="950" height="550" src="https://github.com/totochen/MCU_2023/blob/master/images/Demo_Remote_Control_Car.mp4" autoplay></video>

---
## Remote Control Car
### 功能說明
1. Wifi或Bluetooth聯網：利用Arduino
2. 手機遙控APP：利用手機來遙控汽車.可以前進、左轉、右轉。


### 設計考量與相關技術
**系統設計考量：**<br>
1. 供電方式:電池
2. 聯網方式: WiFi

**所需相關技術：**
1. 電路設計：利用ESP32來設計搖控汽車的電路設計，電路圖如下：
![](https://github.com/totochen/MCU_2023/blob/master/images/circuit.jpg?raw=true)
2. 遙控車完成圖
![](https://github.com/totochen/MCU_2023/blob/master/images/remote_car.jpg?raw=true)
3. 手機遙控器：利用App Inventor 2來設計手機應用程式，透過手機介面來控制汽車的行進方向
![](https://github.com/totochen/MCU_2023/blob/master/images/APP_UI.jpg?raw=true)

### 系統方塊圖
![](https://github.com/totochen/MCU_2023/blob/master/images/system_block.jpg?raw=true)



<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*


