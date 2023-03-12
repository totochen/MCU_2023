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

<iframe width="900" height="500" src="https://www.youtube.com/embed/dE3B0W-H4JQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---
## 智能冰箱
### 應用功能說明
1. 食物倉儲：外出時可隨時查看家裡各處狀況
2. 環境監測：溫濕度感測+瓦斯偵測+空氣品質偵測 
3. 清潔環境：撢灰塵, 除臭
4. 丟棄垃圾：丟棄小型垃圾袋至垃圾車或社區資源回收區
5. 餐飲服務：遞送調味料, 可樂, 水果, 零食
\
### 設計考量與相關技術
**系統設計考量：**<br>
1. 移動方式:共軸雙旋翼
2. 供電方式:電池＋自動充電
3. 聯網方式: WiFi 或 BLE to中控電腦

**所需相關技術：**
1. 飛行姿態偵測與控制: ESP32 + MPU6050 + PID controller
2. 溫濕度感測 & 氣體偵測: HTU21D + MQ2 + MQ7 + MQ135
3. 紅外線遙控: IR-LED 
4. 影像傳輸: ESP32-CAM模組
5. 物品夾具：懸吊掛勾, 磁鐵吸吊
6. 服務器: 具AI加速(GPU)
  - 影像物件偵測辨識: CSL-YOLO
  - 任務規劃控制: Mission Planner with Floorplan

<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*


