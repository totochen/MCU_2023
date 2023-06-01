---
layout: post
title: MPU6050 and KalmanFilter 應用 控制模型飛機
author: [Toto Chen]
category: [Lecture]
tags: [MPU6050, Kalman Filter, Model plane, Remote Control, Arduino]
---

This homework is the application of MPU 6050 to control model airplane. The high-precision MPU6050 gyroscope and accelerometer are used to read the measurement data of the MPU6050 through the processor, and then calculated by Kalman filtering, and the (angular) acceleration is directly output through the serial port. The use of Kalman filter calculation and PCB layout ensures that the MPU6050 receives the least external interference and the highest measurement accuracy.

---

# MPU6050 and KalmanFilter 應用: 控制模型飛機 (MPU6050 and KalmanFilter Application: control model airplane)
### 採用高精度的MPU6050陀螺儀和加速度計，通過處理器讀取MPU6050的測量數據、然後經過卡爾曼濾波計算，通過串口直接輸出(角)加速度。利用卡爾曼濾波計算和PCB佈局，保證了MPU6050收到外接的干擾最小，測量的精度最高。這個專題是應用MPU 6050 控製模型飛機

## 影片展示 : MPU6050 and KalmanFilter 應用: 控制模型飛機 (MPU6050 & Kalman Filter to Control plane)
<div align="center">
<iframe width="640" height="360" src="https://www.youtube.com/embed/0r0MIXIC1fU?autoplay=1&loop=1" title="teapot" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

<div align="center">
<iframe width="640" height="360" src="https://www.youtube.com/embed/oaJ4WSZCa2g?autoplay=1&loop=1" title="filter" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
---

## 功能說明
**1. 藍芽Bluetooth聯網** <br>
**2. 利用陀螺儀和加速度計來模擬飛機飛行** <br>

## 系統設計：
### 1. 電路設計：
![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ5_circuit.png?raw=true)


### 2. 系統架構圖 
![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ5_System_Arch.png?raw=true)


### 3. 程式碼 
**1. Teapot** <br>
![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ5_PRG_Teapot.png?raw=true)

**2. KalmanFilter** <br>
![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ5_PRG_KalmanFilter.png?raw=true)
  
**3. Kalman.h** <br>
![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ5_PRG_Kalman_H.png?raw=true)

**4. Kalman.cpp** <br>
![](https://github.com/totochen/MCU_2023/blob/master/images/PRJ5_PRG_Kalmam_C.png?raw=true)

<br>
<br>

*This site was last updated June 1, 2023.*

