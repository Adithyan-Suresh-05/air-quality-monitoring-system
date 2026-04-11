# air-quality-monitoring-system
Embedded Air Quality Monitoring System using ESP8266 (NodeMCU) that measures air pollution, temperature, and humidity in real-time and displays data locally on LCD and remotely using Blynk IoT platform.
# 🌍 Embedded Air Quality Monitoring System

![IoT](https://img.shields.io/badge/Project-IoT-blue)
![Platform](https://img.shields.io/badge/Platform-ESP8266-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview
This project is an IoT-based Embedded System designed to monitor air quality in real-time. It uses ESP8266 (NodeMCU) along with MQ135 and DHT11 sensors to measure pollution levels, temperature, and humidity.

The system displays data locally on an LCD and remotely through the Blynk cloud platform.

---

## ⚙️ Hardware Components
- ESP8266 NodeMCU  
- MQ135 Gas Sensor  
- DHT11 Sensor  
- 16x2 LCD Display (I2C)  
- Breadboard & Jumper Wires  

---

## 🔌 Circuit Connections

| Component | NodeMCU Pin |
|----------|------------|
| MQ135 | A0 |
| DHT11 | D5 |
| LCD SDA | D2 |
| LCD SCL | D1 |

---

## 🧠 Working Principle
The MQ135 sensor detects air quality levels and sends analog signals to NodeMCU. The DHT11 sensor measures temperature and humidity.

NodeMCU processes the data and:
- Displays values on LCD  
- Sends data to Blynk cloud via Wi-Fi  

---

## 📊 Features
- Real-time monitoring  
- IoT integration (Blynk)  
- LCD display output  
- Remote access via mobile  
- Low-cost system  

---

## 🖥️ System Architecture
(Add your architecture diagram image here)

---

## 🔄 Flowchart
(Add your flowchart image here)

---

## 📱 Blynk Dashboard
(Add screenshot here)

---

## 🚀 How to Run
1. Install Arduino IDE  
2. Install ESP8266 board support  
3. Install libraries:
   - Blynk  
   - DHT  
   - LiquidCrystal_PCF8574  
4. Upload code to NodeMCU  
5. Connect to Wi-Fi  
6. Monitor using LCD & Blynk  

---

## ⚠️ Challenges
- Sensor calibration  
- Wi-Fi stability  
- Data accuracy  

---

## 🔮 Future Improvements
- AI-based prediction  
- SMS alerts  
- Data logging  
- Multi-sensor integration  

---

## 👨‍💻 Author
**Adithyan Suresh**  
Embedded Systems Project – 2026

---

## 📜 License
This project is for academic and educational purposes.
