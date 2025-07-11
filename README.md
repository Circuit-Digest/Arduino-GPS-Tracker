# Arduino GPS Tracker with SIM800L and GeoLinker Cloud

[![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)](https://www.arduino.cc/) 
[![SIM800L](https://img.shields.io/badge/SIM800L-FF6B35?style=for-the-badge&logo=data:image/png+xml;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAACXBIWXMAAAsTAAALEwEAmpwYAAAAnklEQVR4nO2VTQqDMBCFc4N6SeM2u25d9h7qqUxv0J7hK1OyECE/YyNV8MHAQB7zkYHhGfMvAQ1ggXumxNNsGf4EBuCRqRHwKgjQyXCFXyBWA+ilQv8mrtfavwVAwvd9uwCcf0XEj6wKwCWOzP0MKFE1AEG7AWI6NgBlf7wfnHZFVhk4E9BqI9OHpMplsgyfgVsxYAFpCzJZPLrhNfUBCy5g5bl3Vq0AAAAASUVORK5CYII=&logoColor=white)](https://circuitdigest.com/tags/sim800l) 
[![GPS](https://img.shields.io/badge/GPS-4CAF50?style=for-the-badge&logo=data:image/png+xml;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAACXBIWXMAAAsTAAALEwEAmpwYAAAB50lEQVR4nK3WzYvOURQH8GcwnihWbDEmu1lRs2FILEiMBcpfoKlJ8gewYEWDIm87tt4WSCyGHRGi8VLed+R1ZMtHN4d+bs9zn98Mp079+t7vOd9z7z3nPk+j0cGwGifxFN/CnwS2qlN8KfEi3PDLPuMMRnAAZwNLNoreiSZfho94j23obsGZjiF8CF9aN3lvBDzGghr8njiyVExPHYHRIHdMnomkHV9rlAwr41yHWqytxdHwNS3WhyN2RUngOL6k883wExH8NTzZsYzTxHgqoCSQzvJchm2JhHswNXxvYJsy7gU8KgmkCkYy7Dxeo6uCdeFNateMm1p4vCSQevtghl3GWAvuGC5l2CF8KgncwcUM24kfGKxgGwPb0aKY2yWBI7GLZgXrxi18jxa+Ht83qwMYl5wa5HBJYHlc3voMb2I37obvqhYRnMGIHSgJTIkLvdKW1MZwFa9Sjk7E7VHJkiLx75jFcSfDdcgz8S5d2AQEUvVvMaNuwO+xX1eDu6Hd81IKmoaHeIFZBd5svMSDNOG1BSJ4INrxVIFzOjjtO6eDyP7Y/tYWa5tjbd+kklf6/34M358fEyyMobqXz8NkROZHh6SXdg7mxh+AhM37p+QVkf70iOEZnsd3/39JXhHpi85K3lc38CeHJtAPfAd59QAAAABJRU5ErkJggg==&logoColor=white)](https://circuitdigest.com/tags/gps) 
[![GSM](https://img.shields.io/badge/GSM-2196F3?style=for-the-badge&logo=data:image/png+xml;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAMAAADXqc3KAAAAAXNSR0IB2cksfwAAAAlwSFlzAAAOxAAADsQBlSsOGwAAADxQTFRF////////////////////////////////////////////////////////////////////////////////ILFedQAAABR0Uk5TAAc/3v/uV1+mtkd35oYfN54X9g+u9bp9AAAAh0lEQVR4nK3RDwuCMBAF8PdmaiRtiN//I8b6QzJCd00hDXZRgWM8uPuN7WDEh8VNgISIAjQEBwWqmCIqUI9/wH5AGaocDo/piTGH+ZICv0GTZr8pYPupKHMwZml9B8dgegW4E+B4yWE+G7EFuPsKEpdMUxWE9WgCrJzb6yvT96bdntB5OP+eT6PfUk/omDvkAAAAAElFTkSuQmCC&logoColor=white)](https://circuitdigest.com/tags/gsm) 
[![License: MIT](https://img.shields.io/badge/License-MIT-FFD700?style=for-the-badge)](https://opensource.org/licenses/MIT) 
[![CircuitDigest](https://img.shields.io/badge/Tutorial-CircuitDigest-1976D2?style=for-the-badge)](https://circuitdigest.com/microcontroller-projects/                                  )



A cost-effective GPS tracking solution built with Arduino UNO R3, SIM800L GSM module, and NEO-6M GPS module using the GeoLinker Lite library.

![Arduino GPS Tracker Demo](https://github.com/Circuit-Digest/Arduino-GPS-Tracker/blob/fd5cdf357ab65dbac70fde1da3a52f706d3732ad/Images/Title%20Image%203.png)

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

- **Power**: Use a power source with appropriate current capabilities for SIM800L
- **SIM Card**: Requires 2G network (Jio won't work - use Airtel, Vi, BSNL)
- **Upload**: Keep the GPS TX disconnected from Pin 0 while uploading the code.
- **API Key**: Get free API key from [GeoLinker Cloud](https://www.circuitdigest.cloud/)

## 📚 Documentation

For complete setup instructions, circuit diagrams, code explanation, and troubleshooting, see the full tutorial: [Arduino GPS Tracker Tutorial](https://circuitdigest.com/microcontroller-projects/arduino-gps-tracker-using-sim800l-and-neo-6m)

## 🔗 Related Links

- [GeoLinker Lite Library](https://github.com/Circuit-Digest/GeoLinkerLite)
- [GeoLinker Cloud Platform](https://www.circuitdigest.cloud/)
- [ESP32 GPS Tracker](https://circuitdigest.com/microcontroller-projects/simple-gps-tracker-using-esp32-visualize-data-on-map)

## 📄 License

MIT License - see LICENSE file for details.
