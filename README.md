<h1 align="center">Irrigator</h1>

<p align="center">
 A collaborative project made for the farmers, across regions where
 'drip irrigation' & 'sprinkler irrigation' systems are used. It aligns with the present irrigation needs while adhering to the farmers' water conservation principles and feasibility.
</p>

### Tech Stack 
![Python](https://img.shields.io/badge/Python-blue?style=for-the-badge&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white)
![C++](https://img.shields.io/badge/-C++-blue?logo=cplusplus)
  


## Architecture


![Architecture-Irrigator](https://github.com/user-attachments/assets/50d00ed4-5f49-4dd1-b31f-31f747f1281b)

## LoRa-ESP32 Sensor Monitoring Project

### Overview
    
This project utilizes `LoRa` and `ESP32` modules to monitor soil humidity and temperature from a remote farm and display the data live on a mobile application. The `LoRa` transmitter collects sensor data and sends it to the `LoRa` receiver, which is connected to an `ESP32` module acting as a Wi-Fi access point.

## Setup Instructions

1. Connect the LoRa module to the ESP32 as per the connection diagram.
2. Flash the provided receiver code to the ESP32 module.
3. Power the LoRa and ESP32 module using a 5V power source.
4. Connect your mobile phone to the ESP32 Wi-Fi network (SSID: `ESP32_LoRa_Receiver` , Password:  <kbd>123456789</kbd>).
5. Access the live data through the app or a browser using the IP address  <kbd>192.168.4.1</kbd>.

## Usage

After completing the setup, the ESP32 will display live data received from the LoRa transmitter. The mobile app will fetch this data from the ESP32 and present it intuitively.







