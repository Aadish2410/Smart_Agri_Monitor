# 🌿 Smart Agri Monitor – IoT-Based Agriculture Monitoring System

## 📌 Overview
The **Smart Agri Monitor** is an IoT-based project designed to help farmers and researchers monitor real-time field conditions such as **temperature, humidity, soil moisture, and rainfall** using an **ESP32 microcontroller** connected to the **ThingSpeak IoT Cloud**.  
The system is powered by **solar energy** with **18650 Li-ion batteries**, making it a sustainable solution for smart agriculture 🌱⚡  

## 🧠 Features
✅ Real-time monitoring of:
- 🌡️ Temperature & Humidity (DHT11 Sensor)  
- 🌧️ Rain Detection (Analog Rain Sensor)  
- 🌱 Soil Moisture Level (Analog Sensor)  
- ☀️ Solar-powered operation  
- 💻 Data logging to **ThingSpeak Cloud**  
- 🖥️ Live display on **16x2 I2C LCD**

## ⚙️ Components Used
| Component | Description |
|------------|-------------|
| **ESP32 Dev Module** | Main controller with built-in WiFi |
| **DHT11 Sensor** | Measures temperature & humidity |
| **Rain Sensor** | Detects rainfall levels |
| **Soil Moisture Sensor** | Measures soil water content |
| **16x2 LCD (I2C)** | Displays sensor readings |
| **Solar Panel + TP4056 + 18650 Cells** | Power source with charging circuit |

## 🪜 Circuit Diagram
![Circuit Diagram](Screenshot%202025-10-14%20232710.png)

## 💻 Arduino Code
Refer to `Smart_Agri_Monitor.ino` for complete implementation.

## 📈 ThingSpeak Setup
1. Create a ThingSpeak account at [thingspeak.com](https://thingspeak.com).
2. Create a new channel with fields:  
   - Field 1: Temperature  
   - Field 2: Soil Moisture  
   - Field 3: Rain  
   - Field 4: Humidity  
3. Replace your **Channel Number** and **Write API Key** in the code.
4. Upload using **Arduino IDE** with ESP32 board installed.

## ✨ Authors
👩‍💻 **Aadish Ninawe**  
👨‍💻 **Prasad Ambure**  
👨‍💻 **Ayush Dhage**  
👨‍💻 **Aditya Bhosale**

## 🧾 License
Open-source under **MIT License**.
