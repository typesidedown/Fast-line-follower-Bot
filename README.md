![Embedded](https://img.shields.io/badge/Embedded-Systems-008080?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Teensy%204.1-blue?style=for-the-badge&logo=arduino)
![Language](https://img.shields.io/badge/Language-C%2B%2B-00599C?style=for-the-badge&logo=cplusplus)
![IDE](https://img.shields.io/badge/PlatformIO-FF6C37?style=for-the-badge&logo=platformio&logoColor=white)
![IMU](https://img.shields.io/badge/Sensor-IMU-success?style=for-the-badge)
![SPI](https://img.shields.io/badge/Protocol-SPI-orange?style=for-the-badge)
![I2C](https://img.shields.io/badge/Protocol-I2C-orange?style=for-the-badge)
![PID](https://img.shields.io/badge/Control-PID%20Tuned-red?style=for-the-badge)
![Encoder](https://img.shields.io/badge/Feedback-Quadrature%20Encoder-blueviolet?style=for-the-badge)
![Differential Drive](https://img.shields.io/badge/Drive-Differential-black?style=for-the-badge)

# Line Follower Robot

A line-following robot project built with PlatformIO for Teensy 4.0 board.

## Description

This project implements a line follower robot using infrared sensors for line detection, an IMU for orientation, an OLED display for status, and motor control for movement.

## Hardware Requirements

- Teensy 4.0 microcontroller
- Infrared line sensors
- BMI160 IMU sensor
- SSD1306 OLED display
- Motor drivers and motors

## Software Requirements

- PlatformIO IDE
- Arduino framework

## Build and Upload

1. Open the project in PlatformIO.
2. Build the project: `pio run`
3. Upload to the board: `pio run --target upload`

## Usage

Power on the robot and place it on a line track. The robot will follow the line autonomously.

## Files

- `src/main.cpp`: Main program loop
- `src/sensors.cpp`: Line sensor handling
- `src/movement.cpp`: Motor control
- `src/imu.cpp`: IMU sensor integration
- `src/oled.cpp`: OLED display management
- `src/config.cpp`: Configuration settings
