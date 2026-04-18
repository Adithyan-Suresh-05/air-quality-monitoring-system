# air-quality-monitoring-system
Embedded Air Quality Monitoring System using ESP8266 (NodeMCU) that measures air pollution, temperature, and humidity in real-time and displays data locally on LCD and remotely using Blynk IoT platform.
# 🌍 Embedded Air Quality Monitoring System for Urban Environments

## 📌 Project Overview
This project is an Embedded System designed to monitor air quality in real-time using ESP8266 (NodeMCU). It measures air pollution, temperature, and humidity using sensors and displays the data locally on an LCD and remotely using the Blynk IoT platform.

---

## 🎯 Objectives
- Monitor air quality using MQ135 sensor  
- Measure temperature and humidity using DHT11  
- Display real-time data on LCD  
- Send data to cloud using IoT (Blynk)  
- Enable remote monitoring  

---

## ⚙️ Components Used
- ESP8266 NodeMCU  
- MQ135 Gas Sensor  
- DHT11 Sensor  
- 16x2 LCD Display (I2C)  
- Breadboard  
- Jumper Wires  
- Power Supply  

---

## 🔌 Circuit Connections

| Component | NodeMCU Pin |
|----------|------------|
| MQ135 (Analog) | A0 |
| DHT11 (Data) | D5 |
| LCD SDA | D2 |
| LCD SCL | D1 |
| VCC | 3.3V / VIN |
| GND | GND |

---

## 🧠 Working Principle
The MQ135 sensor detects air pollution levels and sends analog signals to the NodeMCU. The DHT11 sensor provides temperature and humidity data. The NodeMCU processes this data and displays it on the LCD. At the same time, it sends the data to the Blynk cloud platform using Wi-Fi, allowing remote monitoring.

---

## 📊 Features
- Real-time monitoring  
- IoT integration (Blynk)  
- LCD display output  
- Remote access via mobile  
- Low-cost system  

---

## 📱 Blynk Dashboard
The system sends data to the Blynk platform where users can view:
- Air Quality  
- Temperature  
- Humidity  

---

## 🚀 How to Run

1. Install Arduino IDE  
2. Install ESP8266 board support  
3. Install required libraries:
   - Blynk
   - DHT
   - LiquidCrystal_PCF8574
4. Connect NodeMCU to PC  
5. Upload the code  
6. Open Serial Monitor  
7. View data on LCD and Blynk dashboard  

---

## ⚠️ Challenges
- Sensor calibration (MQ135)  
- Wi-Fi connectivity issues  
- Accurate data measurement  

---

## 🔮 Future Scope
- SMS/Alert system  
- AI-based pollution prediction  
- Data logging system  
- Mobile app development  
- Multi-gas detection  

---

## 📜 License
This project is for educational purposes.
