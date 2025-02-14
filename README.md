# ESP8266-Based IoT Kit

## Overview
This repository contains an ESP8266-based IoT kit that integrates multiple sensors, actuators, and modules to demonstrate various IoT applications. The project is designed for educational and experimental purposes, allowing users to interact with different components and understand their working.

## Features
- **Real-time Monitoring and Control**: Sensors collect data and ESP8266 transmits it to a web interface.
- **Multiple Input/Output Modules**: Includes switches, LEDs, motors, and displays.
- **Wireless Communication**: Bluetooth and RFID for seamless interaction.
- **Multiple Sensors**: Environmental and motion sensors for diverse applications.

## Components Used
- **Display:** 7-Segment Display
- **Sensors:**
  - AccurateUltrasonic Sensor
  - IR Sensor
  - LDR (Light Dependent Resistor)
  - MPU6050 (Accelerometer & Gyroscope)
  - BMP180 (Barometric Pressure Sensor)
  - DHT11 (Temperature & Humidity Sensor)
- **Actuators & Modules:**
  - Servo Motor
  - DC Motor
  - L293D Motor Driver
  - Touch Module
  - Rotary Encoder
- **Communication Modules:**
  - Bluetooth Module
  - RFID Module
- **User Inputs:**
  - Switches
  - Touch Inputs

## Installation & Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/nikhiltembhurne321/Esp8266_Based_Iot_kit.git
   ```
2. Install the required libraries in the Arduino IDE:
   - ESP8266WiFi
   - Adafruit_Sensor
   - DHT
   - MPU6050
   - Adafruit_BMP180
   - RFID
3. Upload the code to the ESP8266 board.
4. Connect the components as per the wiring diagram provided.
5. Power up the board and monitor the output via Serial Monitor or a web interface.

## Usage
- Monitor sensor data in real time.
- Control actuators remotely using Bluetooth or a web-based dashboard.
- Implement IoT applications like home automation, security systems, and environmental monitoring.

## Future Enhancements
- Integration with a cloud server for remote data logging.
- Mobile app support for better user interaction.
- Addition of more advanced sensors and actuators.



## Author
[Nikhil Tembhurne](https://github.com/nikhiltembhurne321)

