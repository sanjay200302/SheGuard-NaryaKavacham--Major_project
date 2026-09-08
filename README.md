# Narya Kavacham – Women’s Safety System

## 📖 Overview
**Narya Kavacham** is an Android + Bluetooth‑enabled wearable system designed to provide **instant, discreet SOS alerts** for women in emergency situations. Unlike traditional safety apps that require manual phone interaction, Narya Kavacham integrates a **mobile application** with a **low‑cost wearable band** to deliver alerts within **2–4 seconds**, even when the phone is locked or inaccessible.

This project was developed as a **final year engineering project** and demonstrates how mobile and IoT technologies can be combined to create practical, deployable safety solutions.

---

## ✨ Features
- **Multi‑trigger SOS activation**
  - In‑app SOS button
  - Shake detection (accelerometer‑based)
  - Bluetooth wearable band button
  - Loud siren for attention
- **Background monitoring**
  - Works even when the app is minimized or the phone is locked
- **Offline capability**
  - SOS alerts sent via SMS (no internet required)
- **Lightweight hardware**
  - Microcontroller + Bluetooth module + push button
- **Performance**
  - Reduces SOS response time from 18–25s (manual) → 2–4s (automated)
  - ~92% shake detection accuracy
  - ~95% Bluetooth trigger reliability

---

## 🏗️ System Architecture
### Android App
- Emergency contact management  
- SOS alert module (SMS automation)  
- Shake detection module  
- Bluetooth listener module  
- Background service module  
- Siren module  

### Wearable Band
- Microcontroller (Arduino/ESP32)  
- Bluetooth module (HC‑05/BLE)  
- Push button + battery  

### Communication
Bluetooth → Smartphone → SMS → Emergency contacts  

---

## 🔧 Tech Stack
- **Mobile:** Android Studio, Java, XML, Android SDK  
- **Hardware:** Arduino IDE, HC‑05/BLE, Microcontroller (Arduino/ESP32)  
- **APIs:** Android Bluetooth API, SMS Manager API, Sensor Framework  
- **Tools:** Breadboard, jumper wires, multimeter  

---

## 🚀 Getting Started
### Prerequisites
- Android Studio (latest version)  
- Arduino IDE  
- Android device with Bluetooth  
- Arduino/ESP32 board  

### Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/sanjay200302/Narya-Kavacham.git
   cd Narya-Kavacham
2. **Android App**

        Open in Android Studio

        Configure permissions for SMS, Bluetooth, and sensors

        Build & run on device

3. **Wearable Band**

        Upload firmware via Arduino IDE

        Pair band with smartphone via Bluetooth

4. **Emergency Contacts**

       Add trusted contacts in the app

       Test SOS triggers (shake, button, siren)

📊 **Results**
        
       Response Time: 2–4 seconds (vs. 18–25 seconds manual)

       Shake Detection Accuracy: ~92%

       Bluetooth Trigger Reliability: ~95%

  SMS Delivery Success: ~95%

        Background Monitoring: Continuous, even when app closed

🔮 **Future Enhancements**
  
        GPS‑based live location sharing

        Alerts via instant messaging platforms

        AI‑driven threat detection (motion/behavior analysis)

        Integration with smartwatches and consumer wearables

        Cross‑platform support (iOS)

        Advanced power management for wearable band

📚 **References**

  Sommerville, Software Engineering, 9th ed., Pearson Education, 2011

  Sharma et al., Mobile‑Based Women Safety Application, IJCAT, 2025

  Verma et al., IoT‑Enabled Smart Safety Device, IJITST, 2024

  Reddy & Banerjee, IoT‑Based Wearable Wrist Band, JESA, 2023

  Google Developers – Android Bluetooth Low Energy Overview

  Arduino Documentation – Getting Started with Arduino and BLE Modules

👩‍💻 **Contributors**

  Sanjay Kumar – AI/ML & Cloud specialization

  Project Team – Final Year Engineering, 2026

📬 **Contact**
  If you’d like to connect, collaborate, or discuss opportunities, feel free to reach out:
  
      Portfolio: https://sanjay200302.github.io/sanjay.com/

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.

