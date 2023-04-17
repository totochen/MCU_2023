---
layout: post
title: 藍芽遙控機器人(Remote Control Robot)
author: [Toto Chen]
category: [Lecture]
tags: [Remote Control, Arduino]
---

This homework is to specify a Remote Control Car, list all Design Considerations and the required technologies, then draw the System Block Diagram.

---
# 藍芽遙控機器人 (Remote Control Robot)

## 影片展示 : 藍芽遙控機器人 (Remote Control Robot)
<div align="center">
<iframe width="320" height="560" src="https://www.youtube.com/embed/kDWMcbzpWGE?autoplay=1&loop=1" title="Demo Remote Control Car" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
---

## 功能說明
**1. Wifi或Bluetooth聯網：利用手機熱點WiFi連線** <br>
**2. 手機遙控APP：利用手機來遙控汽車.可以前進、後退、左轉、右轉。** <br>


## 系統設計：
### 供電方式:電池 
### 聯網方式: WiFi

### 1. 電路設計：利用ESP32來設計搖控汽車的電路設計，電路圖如下：

![](https://github.com/totochen/MCU_2023/blob/master/images/circuit.jpg?raw=true&width=100x )


### 2. 遙控車完成圖 

![](https://github.com/totochen/MCU_2023/blob/master/images/remote_car.jpg?raw=true)



### 3. 手機遙控器：利用App Inventor 2來設計手機應用程式，透過手機介面來控制汽車的行進方向 

![](https://github.com/totochen/MCU_2023/blob/master/images/APP_UI.jpg?raw=true)


## Arduino Code(Wi-Fi版)





<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*

