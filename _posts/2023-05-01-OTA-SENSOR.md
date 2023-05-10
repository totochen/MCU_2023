---
layout: post
title: OTA(Over The Air)
author: [Toto Chen]
category: [Lecture]
tags: [IoT]
---

The Internet of Smart Home Appliances is the remote control of home appliances through mobile phones. This project uses mobile phones to simulate remote control of home lights through the Internet. The content of the page list all Design Considerations and the required technologies.

---

# OTA (Over The Air)
## 非同步ESP32_Webserver 控制家電關開關

---

## 功能說明
**1. 透過WiFi 聯網 ** <br>
**2. 透過手機->Webserver->遙控LED燈  ** <br>


## 系統設計：
### 聯網方式: WiFi
### 操作方式:WebUI

### 1. 電路設計：利用ESP32來設計家用LED燈的控制電路設計，電路圖如下：

![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ4_CIRCUIT_DIAG.jpg?raw=true){:height="300px" width="400px"}


### 2. 手機操作遙控介面完成圖 
###控制畫面及顯示LED 是ON 狀態
![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ4_LED_ON.jpg?raw=true){:height="300px" width="200px"}
<br>
###控制畫面及顯示LED 是OFF 狀態
![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ4_LED_OFF.jpg?raw=true){:height="300px" width="200px"}

### 3. 程式設計： 
![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ4_PRG.png?raw=true)



<br>
<br>

*This site was last updated May 07, 2023.*

