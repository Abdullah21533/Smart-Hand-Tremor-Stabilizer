# Smart-Hand-Tremor-Stabilizer

## 🩺 Overview

The Smart Hand Tremor Stabilizer is an ESP32-based biomedical assistive device designed to reduce unwanted hand tremors using a counter-vibration mechanism. The system continuously monitors hand motion through a GY-61 accelerometer sensor and generates controlled out-of-phase vibrations using vibration motors to improve hand stability.

This project demonstrates the integration of embedded systems, motion sensing, vibration control, and real-time monitoring for assistive healthcare and rehabilitation applications.

---

## 🚀 Features

* Real-time hand tremor detection
* Counter-vibration stabilization mechanism
* ESP32-based embedded control
* OLED display interface
* User-friendly push-button controls
* Visual LED status indicators
* Portable battery-powered operation
* Compact and low-cost design

---

## 🛠 Hardware Components

| Component              | Function                     |
| ---------------------- | ---------------------------- |
| ESP32 Microcontroller  | Main controller              |
| GY-61 Accelerometer    | Hand motion detection        |
| Vibration Motors       | Counter-vibration generation |
| Motor Driver Module    | Motor control                |
| OLED SSD1306 Display   | System monitoring            |
| Push Buttons           | User control                 |
| LEDs                   | Status indication            |
| Li-ion Battery         | Portable power source        |
| TP4056 Charging Module | Battery charging             |
| DC-DC Boost Converter  | Voltage regulation           |

---

## ⚙ Working Principle

### Tremor Detection

The GY-61 accelerometer continuously measures hand movement and vibration patterns. Motion data is transmitted to the ESP32 for processing.

### Counter-Vibration Stabilization

When tremors are detected, the ESP32 activates vibration motors through the motor driver. The motors generate controlled vibrations in the opposite phase of the detected tremor, helping reduce unwanted hand movement.

### Real-Time Monitoring

The OLED display provides live system information including:

* System status
* Motor activity
* Operating mode
* Device information

---

## 🎮 User Controls

| Button   | Function                |
| -------- | ----------------------- |
| Button 1 | Toggle vibration motors |
| Button 2 | Toggle LED indicators   |

### LED Indicators

* Power status
* Device activity
* Motor operation status

---

## 💻 Software Stack

* Arduino IDE
* ESP32 Framework
* Wire Library
* Adafruit GFX Library
* Adafruit SSD1306 Library
* PWM Motor Control

---

## 📂 Repository Structure

```text
Smart-Hand-Tremor-Stabilizer
│
├── README.md
├── hand_stirlize.ino
├── Hand Tremor Stabilizer Report.pdf
├── Circuit_Diagram.png
├── Hardware_Photo_01.jpeg
├── Hardware_Photo_02.jpeg
├── Hardware_Photo_03.jpeg
├── Hardware_Photo_04.jpeg
├── Hardware_Photo_05.jpeg
└── LICENSE
```

---

## 📸 Project Demonstration

The system successfully:

1. Detects hand tremors using the GY-61 sensor.
2. Processes vibration data through ESP32.
3. Generates counter-vibrations using vibration motors.
4. Displays system information on OLED.
5. Provides real-time stabilization assistance.

---

## 🎯 Applications

* Assistive Healthcare Devices
* Rehabilitation Systems
* Biomedical Engineering Projects
* Wearable Technology Research
* Embedded System Development
* Motion Stabilization Research

---

## 🔬 Future Improvements

* AI-based tremor prediction
* Adaptive vibration control
* Bluetooth mobile application
* Cloud-based monitoring
* Wearable glove implementation
* Advanced motion analysis algorithms

---

## 👨‍💻 Author

### Muhammad Abdullah

BS Software Engineering

The Islamia University of Bahawalpur (IUB), Pakistan

Research Interests:

* Embedded Systems
* Biomedical Engineering
* Artificial Intelligence
* Internet of Things
* Assistive Technologies
* Robotics and Automation

---

## 👨‍🏫 Supervisor

### Dr. Engr. Dileep Kumar

Faculty of Engineering

Department of Electronic Engineering

The Islamia University of Bahawalpur (IUB)

---

## 📜 License

This project is released under the MIT License.

---

## ⭐ Acknowledgment

This project was developed as a biomedical assistive technology prototype to explore the application of embedded systems and vibration control techniques for hand tremor stabilization and rehabilitation support.
