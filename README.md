# Real-Time-GPS-Location-Display-using-ESP32-and-NEO-6M-with-I2C-LCD-
Real-time GPS location tracking system using ESP32 and NEO-6M module. The device reads latitude and longitude data from the GPS and displays it on a 16x2 I2C LCD, demonstrating GPS communication and embedded system integration. 

This project demonstrates a **Real-Time GPS Location Tracking System** using **ESP32**, **NEO-6M GPS Module**, and a **16x2 I2C LCD Display**.  
The system reads **latitude and longitude** from the GPS module and displays the coordinates on the LCD as well as the Serial Monitor.

---

## 🚀 Features
- Real-time GPS location tracking
- Displays **Latitude and Longitude**
- Uses **TinyGPS++ library** for GPS data decoding
- Displays data on **16x2 LCD via I2C**
- Serial Monitor output for debugging

---

## 🧰 Components Required
- ESP32 Development Board
- NEO-6M GPS Module
- 16x2 LCD Display with I2C module
- Jumper wires
- Breadboard
- USB cable

---

## 🔌 Circuit Connections

### GPS Module → ESP32
| GPS Pin | ESP32 Pin |
|--------|-----------|
| VCC | 3.3V / 5V |
| GND | GND |
| TX | GPIO16 |
| RX | GPIO17 |

### LCD (I2C) → ESP32
| LCD Pin | ESP32 Pin |
|--------|-----------|
| VCC | 5V |
| GND | GND |
| SDA | GPIO21 |
| SCL | GPIO22 |

---

## 📂 Libraries Used
Install the following libraries from the Arduino Library Manager:

- TinyGPS++
- LiquidCrystal_I2C
- Wire

---


---

## 📊 Output Example

Lat: 12.3456
Lng: 77.6543

---
## 🎯 Applications
- Vehicle Tracking
- Location Monitoring
- Navigation Systems
- IoT Tracking Devices

---

## 👨‍💻 Author
**Maaz Khanapuri**

---

⭐ If you like this project, consider giving it a **star** on GitHub!
