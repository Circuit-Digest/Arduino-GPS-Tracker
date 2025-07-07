# Arduino GPS Tracker with SIM800L and GeoLinker Cloud

[![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)](https://www.arduino.cc/) 
[![SIM800L](https://img.shields.io/badge/SIM800L-FF6B35?style=for-the-badge&logo=data:image/svg+xml;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAACXBIWXMAAAsTAAALEwEAmpwYAAAAnklEQVR4nO2VTQqDMBCFc4N6SeM2u25d9h7qqUxv0J7hK1OyECE/YyNV8MHAQB7zkYHhGfMvAQ1ggXumxNNsGf4EBuCRqRHwKgjQyXCFXyBWA+ilQv8mrtfavwVAwvd9uwCcf0XEj6wKwCWOzP0MKFE1AEG7AWI6NgBlf7wfnHZFVhk4E9BqI9OHpMplsgyfgVsxYAFpCzJZPLrhNfUBCy5g5bl3Vq0AAAAASUVORK5CYII=&logoColor=white)](https://en.wikipedia.org/wiki/SIM800L) 
[![GPS](https://img.shields.io/badge/GPS-4CAF50?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDJDMTMuMSAyIDE0IDIuOSAxNCA0QzE0IDUuMSAxMy4xIDYgMTIgNkMxMC45IDYgMTAgNS4xIDEwIDRDMTAgMi45IDEwLjkgMiAxMiAyWk0yMSAxMC41QzIxIDYuMTEgMTYuNDEgMyAxMiAzQzcuNTkgMyAzIDYuMTEgMyAxMC41QzMgMTMuMzggNS4zOSAxNi4xOSA5IDE4Ljc2VjIySDEyVjIyVjE4Ljc2QzE1LjYxIDE2LjE5IDE4IDEzLjM4IDE4IDEwLjVaIiBmaWxsPSJ3aGl0ZSIvPgo8Y2lyY2xlIGN4PSIxMiIgY3k9IjEwIiByPSIyIiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4K&logoColor=white)](https://en.wikipedia.org/wiki/Global_Positioning_System) 
[![GSM](https://img.shields.io/badge/GSM-2196F3?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTIgMTdIMTBWMTlIMlYxN1oiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0yIDEzSDEyVjE1SDJWMTNaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMiA5SDE0VjExSDJWOVoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0yIDVIMTZWN0gyVjVaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAgMTdIMjJWMTlIMjBWMTdaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMTggMTNIMjJWMTVIMThWMTNaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMTYgOUgyMlYxMUgxNlY5WiIgZmlsbD0id2hpdGUiLz4KPHA+Cjxzdmcgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+Cjwvc3ZnPgo=&logoColor=white)](https://en.wikipedia.org/wiki/GSM) 
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
