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
**1. 藍芽Bluetooth聯網** <br>
**2. 手機遙控APP：利用手機來遙控汽車.可以前進、後退、左轉、右轉。** <br>


## 系統設計：
### 供電方式:鋰電池 3.7V x2 
### 聯網方式: 藍芽(Bluetooth)
### 操作方式:WebUI
### 移動方式:兩輪
### 原始套件:
![](https://github.com/totochen/MCU_2023/blob/master/images/org_tools.jpg?raw=true){:height="500px" width="600px"}

### 1. 電路設計：利用ESP32來設計搖控汽車的電路設計，電路圖如下：

![](https://github.com/totochen/MCU_2023/blob/master/images/circuit.jpg?raw=true){:height="500px" width="600px"}


### 2. 遙控車完成圖 

![](https://github.com/totochen/MCU_2023/blob/master/images/remote_car.jpg?raw=true){:height="500px" width="600px"}


### 3. 系統架構圖 

![](https://github.com/totochen/MCU_2023/blob/master/images/Sys_Block_1.jpg?raw=true){:height="500px" width="600px"}


### 4. 手機遙控器：利用App Inventor來設計手機應用程式，透過手機介面來控制汽車的行進方向 

![](https://github.com/totochen/MCU_2023/blob/master/images/APP_UI.jpg?raw=true){:height="500px" width="250px"}
![](https://github.com/totochen/MCU_2023/blob/master/images/APP_Block.png?raw=true){:height="500px" width="450px"}

## Arduino Code(藍芽)

![](https://github.com/totochen/MCU_2023/blob/master/images/PRG_2.png?raw=true)



<br>
<br>

*This site was last updated April 17, 2023.*

