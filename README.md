## 2.4 GHz BLE/Wi-Fi Jammer A 2.4 GHz 

BLE/Wi-Fi jammer project by Dextelektro How the code works When the ESP32 is powered on and the program begins executing, the blue indicator light on the ESP32 turns on to signal that the program is running. The 0.96-inch LCD screen displays "HSPI" and "VSPI" to indicate that these interfaces are active; the device then continuously emits random frame signals designed to disrupt signals operating in the 2.4 GHz frequency range. 

## About the code and device

Signal strength and frame transmission speed are adjustable. Please note that this code is intended for prototyping; for maximum performance and power, you can modify and update the code using platforms such as Arduino IDE, ESP-IDF, or PlatformIO (via VS Code or other applications). 

## Disclaimer Please use this code responsibly. 

*The use of such code and devices is strictly prohibited in many countries due to laws regarding signal jammers. I accept no liability for any illegal use of this device or code.*

## Components
- ESP32 Dev Module
- 0.96" OLED display
- Two NRF24 PA/LNA modules
- Battery
- TP4056
- WS2812

## Wiring
HSPI SCK 14 MISO 12 MOSI 13 CS 15 CE 26 VCC 3.3V GND GND VSPI SCK 18 MISO 19 MOSI 23 CS 15 CE 4 VCC 3.3V GND GND OLED 0.96" SDA 21 SCL 22 VCC 5V GND GND WS2812 DI 5 VCC 5V GND GND

## How to upload the program Download or copy the program, then open it in the Arduino IDE. Select the "ESP32 Dev Module" board and upload the file/program. Download the following libraries: - RF24 - EZButton - Adafruit NeoPixel Set the upload speed to 115200, select the ESP32 Dev Module port (e.g., COM5), and upload the program.

Follow my TikTok account: Dextelektro
