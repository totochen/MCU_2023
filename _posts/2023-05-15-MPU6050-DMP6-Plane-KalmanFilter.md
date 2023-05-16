---
layout: post
title: MPU6050 and KalmanFilter 應用: 控制模型飛機 (MPU6050 and KalmanFilter Application: control model airplane)
author: [Toto Chen]
category: [Lecture]
tags: [MPU6050, Kalman Filter, Model plane, Remote Control, Arduino]
---

This homework is the application of MPU 6050 to control model airplane. The high-precision MPU6050 gyroscope and accelerometer are used to read the measurement data of the MPU6050 through the processor, and then calculated by Kalman filtering, and the (angular) acceleration is directly output through the serial port. The use of Kalman filter calculation and PCB layout ensures that the MPU6050 receives the least external interference and the highest measurement accuracy.

---

# MPU6050 and KalmanFilter 應用: 控制模型飛機 (MPU6050 and KalmanFilter Application: control model airplane)
## 採用高精度的MPU6050陀螺儀和加速度計，通過處理器讀取MPU6050的測量數據、然後經過卡爾曼濾波計算，通過串口直接輸出(角)加速度。利用卡爾曼濾波計算和PCB佈局，保證了MPU6050收到外接的干擾最小，測量的精度最高。這個專題是應用MPU 6050 控製模型飛機

## 影片展示 : MPU6050 and KalmanFilter 應用: 控制模型飛機 (MPU6050 & Kalman Filter to Control plane)
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

*This site was last updated May 15, 2023.*

