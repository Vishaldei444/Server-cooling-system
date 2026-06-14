# 🌡️ Server Room Cooling System

## 📖 Overview
The Server Room Cooling System is an Arduino-based automation project designed to monitor temperature and humidity inside a server room. Using a DHT22 sensor, the system continuously reads environmental conditions and automatically adjusts fan speed based on temperature levels. Status LEDs provide visual indications of the room condition.
This project demonstrates the use of sensors, PWM control, and real-time monitoring for industrial safety applications.

## 🎯 Objectives
- Monitor server room temperature and humidity.
- Automatically control cooling fan speed.
- Provide visual status indication using LEDs.
- Display real-time readings on the Serial Monitor.
- Simulate an industrial cooling system using Arduino.

## 🛠 Hardware Components

| Component | Quantity |
|------------|------------|
| Arduino UNO | 1 |
| DHT22 Sensor | 1 |
| Green LED | 1 |
| Yellow LED | 1 |
| Red LED | 1 |
| PWM LED (Fan Simulation) | 1 |
| 220Ω Resistors | 4 |
| Breadboard | 1 |
| Jumper Wires | As Required |

---

## 🔌 Circuit Connections

| Component | Arduino Pin |
|------------|------------|
| DHT22 DATA | D2 |
| PWM LED (Fan Simulation) | D9 |
| Green LED | D4 |
| Yellow LED | D5 |
| Red LED | D6 |
| DHT22 VCC | 5V |
| DHT22 GND | GND |

## 📚 Library Used

Install the following Arduino library:

#include <DHT.h>

Library:
- DHT Sensor Library

## 🎥 Project Demo Video

[Watch Demo Video](https://github.com/USERNAME/REPOSITORY_NAME/blob/main/server-room-cooling-system-demo.mp4)
