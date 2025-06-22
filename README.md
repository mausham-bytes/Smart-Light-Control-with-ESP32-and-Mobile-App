# Smart-Light-Control-with-ESP32-and-Mobile-App
A simple IoT project to control an LED using an ESP32 and the Blynk mobile app via Wi-Fi. Built for CodTech’s IoT Internship 2025 – Task 1: Smart Light Control.
# Smart Light Control with ESP32 and Mobile App

This project demonstrates how to control an LED using the ESP32 microcontroller and a mobile app via Wi-Fi using the Blynk IoT platform.

## 🔧 Hardware Setup

### Components:
- ESP32 Dev Board
- LED
- 220Ω Resistor
- Breadboard + Jumper Wires

### Circuit Diagrams:

#### Breadboard Setup
![Breadboard Circuit](hardware/circuit_breadboard.png)

#### Schematic
![Schematic](hardware/circuit_diagram.png)

## 💻 Software Setup

1. Install Arduino IDE
2. Add ESP32 board URL to Board Manager:
   ```
   https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
   ```
3. Install **Blynk Library**
4. Upload the sketch from `firmware/Blynk_LED_Control.ino` to your ESP32
5. Create a Blynk Project, add a Button widget for GPIO2

## 📲 Mobile App

Use the **Blynk IoT app** to control the LED from your phone.

## ✅ Features
- Real-time LED control via mobile
- Wi-Fi connectivity using ESP32

---

This is part of the **CodTech IoT Internship 2025 - Task 1**.
