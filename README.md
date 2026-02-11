# Jammer-Dual-Nrf-24-Ble
Projek jammer ble/wifi 2,4 GHz by Dextelektro

Tiktok = Dextelektro

Github = Dextelektro

Shopee = storediyprojek

Follow me because it will make me more enthusiastic and motivated

Jammer dual NRF24 BY Dextelektro

Saat esp32 menyala dan progam berjalan maka lampu biru pada esp32 akan menyala menandakan bahwa progam sudah berjalan
dan layar oled 0.96 akan menyala menandakan bahwa HSPI dan VSPI sudah berjalan dan akan mengeluarkan sinyal radio/sinyaal jammer yang akan mengacaukan perangkat yang menggunakan sinyal 2,4Ghz

In English

2.4 GHz BLE/WiFi jammer project  
When the ESP32 is powered on and the program runs, the blue light on the ESP32 will turn on, indicating that the program is running,  
and the 0.96 OLED screen will light up, indicating that HSPI and VSPI are running and will emit radio/jammer signals that will interfere with devices using 2.4GHz signals.

## komponen/component

- Esp32 Dev modul
- oled display 0.96
- two NRF24 PA/LNA
- battery
- TP4056
- WS2812

## Wiring 

HSPI

SCK   14 

MISO  12

MOSI  13

CS    15 

CE    26

VCC   3.3V

GND   GND

 
VSPI 

SCK   18 

MISO  19

MOSI  23

CS    15

CE    4

VCC   3.3V

GND   GND

OLED 0.96
SDA   21
SCL   22
VCC   5V
GND   GND

WS2812
DI    5
VCC   5V
GND   GND

## Cara uploud/How to upload
Unduh Progam/salin link lalu buka di arduino ide 3.9, Pilih board esp32 dev modul, Uploud file 
unduh libary 
RF24
EZbutton
Adafruitneopixel
Kecepatan unduh 115200, Lalu masukan port esp32 dev modul contoh (com5) dan unduh progam

In Engish
Download the program/copy the link and then open it in Arduino IDE 3.9, select the ESP32 Dev Module board, upload the file.  
Download the libraries:  
RF24  
EZButton  
Adafruit NeoPixel  
Download speed 115200, then enter the ESP32 Dev Module port, for example (COM5), and upload the program.

## Disklaimer
Alat jammer ini bertujuan untuk memberikan gambaran dan referensi serta tujuan pembelajaran. Kami tidak bertanggung atas penggunaan secara ilegal. Segala tindakan yang diambil berdasarkan informasi ini menjadi tanggung jawab masing-masing pengguna.

In english
This jammer device is intended to provide an overview, reference, and learning objectives. We are not responsible for illegal use. Any actions taken based on this information are the responsibility of each individual user.

