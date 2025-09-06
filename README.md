# Smart Home Automation using Arduino + IoT

## Project Overview
This is my **internship final project** in IoT & Embedded Systems.  
The idea is to **control home appliances (like a bulb and a fan)** using my **mobile phone** through the **Blynk IoT app**.  
- Arduino works as the brain.  
- ESP8266 WiFi module connects Arduino to the internet.  
- Relays act as ON/OFF switches for appliances.  

---

## ⚙️ Components Used
- Arduino Uno  
- ESP8266 WiFi Module  
- 2-Channel Relay Module  
- Bulb (or LED for demo)  
- Fan (or any load for demo)  
- Jumper wires, Power supply  

---

## 🔌 Working Principle
1. The **Blynk mobile app** sends commands when I press a button.  
2. ESP8266 receives the signal and passes it to Arduino.  
3. Arduino switches ON/OFF the relay.  
4. Relay controls the appliance (like bulb/fan).  

📱 Basically → *Phone → WiFi → Arduino → Relay → Appliance*  
