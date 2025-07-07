# Arduino GPS Tracker with SIM800L and GeoLinker Cloud

[![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)](https://www.arduino.cc/) 
[![SIM800L](https://img.shields.io/badge/SIM800L-FF6B35?style=for-the-badge&logo=mobile&logoColor=white)](https://en.wikipedia.org/wiki/SIM800L) 
[![GPS](https://img.shields.io/badge/GPS-4CAF50?style=for-the-badge&logo=map-marker&logoColor=white)](https://en.wikipedia.org/wiki/Global_Positioning_System) 
[![GSM](https://img.shields.io/badge/GSM-2196F3?style=for-the-badge&logo=wifi&logoColor=white)](https://en.wikipedia.org/wiki/GSM) 
[![License: MIT](https://img.shields.io/badge/License-MIT-FFD700?style=for-the-badge)](https://opensource.org/licenses/MIT) 
[![CircuitDigest](https://img.shields.io/badge/Tutorial-CircuitDigest-1976D2?style=for-the-badge)](https://circuitdigest.com/microcontroller-projects/arduino-gps-tracker-using-sim800l-and-geolinker-cloud)

A cost-effective GPS tracking solution built with Arduino UNO R3, SIM800L GSM module, and NEO-6M GPS module using the GeoLinker Lite library.

![Arduino GPS Tracker Demo](media/image3.gif)

## 🚀 Features

- Real-time GPS tracking with cloud integration
- Memory optimized for Arduino UNO R3's limited RAM
- Web dashboard for live location monitoring
- Historical data logging and CSV export
- Free cloud platform with no monthly fees

## 🛠️ Components

- Arduino UNO R3
- SIM800L GSM module  
- NEO-6M GPS module
- Resistors (4.7kΩ, 10kΩ)
- Breadboard and jumper wires
- 2G SIM card

## 📋 Quick Setup

1. **Install Library**: Search "GeoLinker Lite" in Arduino IDE Library Manager
2. **Wire Components**: Follow the circuit diagram provided
3. **Configure Code**: Set your APN, API key, and device ID
4. **Upload & Run**: Power with external source recommended

## 🔌 Key Connections

| Component | Arduino Pin | Notes |
|-----------|-------------|-------|
| GPS TX | Pin 0 (RX) | Disconnect during upload |
| SIM800L RX | Pin 8 | Via voltage divider |
| SIM800L TX | Pin 9 | Direct connection |
| Reset Control | Pin 2 | Automatic mode switching |

## ⚠️ Important Notes

- **Power**: Use external power bank for SIM800L (insufficient USB power)
- **SIM Card**: Requires 2G network (Jio won't work - use Airtel, Vi, BSNL)
- **Upload**: Disconnect GPS TX from Pin 0 before uploading code
- **API Key**: Get free API key from [GeoLinker Cloud](https://www.circuitdigest.cloud/)

## 📚 Documentation

For complete setup instructions, circuit diagrams, code explanation, and troubleshooting, see the full tutorial: [Arduino GPS Tracker Tutorial](https://circuitdigest.com/microcontroller-projects/arduino-gps-tracker-using-sim800l-and-geolinker-cloud)

## 🔗 Related Links

- [GeoLinker Lite Library](https://github.com/Circuit-Digest/GeoLinkerLite)
- [GeoLinker Cloud Platform](https://www.circuitdigest.cloud/)
- [ESP32 GPS Tracker](https://circuitdigest.com/microcontroller-projects/simple-gps-tracker-using-esp32-visualize-data-on-map)

## 📄 License

MIT License - see LICENSE file for details.
