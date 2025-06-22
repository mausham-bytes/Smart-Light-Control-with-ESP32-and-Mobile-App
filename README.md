# Smart-Light-Control-with-ESP32-and-Mobile-App
A simple IoT project to control an LED using an ESP32 and the Blynk mobile app via Wi-Fi. Built for CodTech’s IoT Internship 2025 – Task 1: Smart Light Control.
# 💡 Smart Light Control with ESP32 and Mobile App

A simple IoT project to control an LED using an ESP32 and the Blynk mobile app via Wi-Fi.  
Built as part of **CodTech’s IoT Internship 2025 – Task 1: Smart Light Control**.

---

## 📦 Project Overview

This project demonstrates wireless LED control using:
- ✅ ESP32 microcontroller  
- ✅ Blynk IoT platform  
- ✅ Mobile app interface  

---

## 🔧 Hardware Setup

### 🧩 Components Required
- ESP32 Dev Board  
- LED (any color)  
- 220Ω Resistor  
- Breadboard  
- Jumper Wires  

### 🔌 Circuit Diagrams

#### 🖼️ Schematic
![Circuit Diagram](hardware/circuit_diagram.png)

#### 🔋 Breadboard Setup
![Breadboard Setup](hardware/breadboard_setup.png)

---

## 💻 Software Setup

1. **Install Arduino IDE**

2. **Add ESP32 board to Board Manager**  
   Paste this URL into **File → Preferences → Additional Board URLs**:
   
   https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

   
3. **Install the Blynk Library**  
Go to **Sketch → Include Library → Manage Libraries** → Search for `Blynk` and install it.

4. **Upload Code**  
Open the file:  

Replace:
- `BLYNK_AUTH_TOKEN`
- `Wi-Fi SSID`
- `Wi-Fi Password`  
with your actual credentials.

5. **Configure Blynk App**
- Create a new project in the Blynk IoT mobile app.
- Add a **Button widget**.
- Set it to **Digital → GPIO2**.
- Set the **Mode** to **Switch** (not Push).

---

## 📱 Mobile App (Blynk IoT)

- Download the **Blynk IoT App** from the [Play Store](https://play.google.com/store/apps/details?id=cloud.blynk) or [App Store](https://apps.apple.com/us/app/blynk-iot/id1551043569)
- Log in or sign up
- Create a new project and get your **auth token** via email
- Use this token in your Arduino code
- Control your LED in real-time!

---

## ✅ Features

- 🔄 Real-time LED control via smartphone  
- 📶 Wireless connectivity with ESP32  
- 📲 Simple mobile interface using Blynk  

---

## 📁 Project Structure

Smart-Light-Control/
├── hardware/
│ ├── breadboard_setup.png
│ └── circuit_diagram.png
├── firmware/
│ └── Blynk_LED_Control.ino
├── .gitignore
├── .gitattributes
├── LICENSE
└── README.md


---

## 📌 Notes

- Make sure the LED is connected with the correct polarity (long leg = +).
- Use a 220Ω resistor in series with the LED to prevent burning it out.
- The ESP32 and your mobile device must be on the **same Wi-Fi network**.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

