
STM32 HC-SR04 OLED Distance Monitor

 Overview

This project measures distance using the HC-SR04 ultrasonic sensor and displays the measured value on an OLED display using an STM32F103C8T6 microcontroller.

The distance is also transmitted through UART and monitored using an ESP32 serial bridge.

---

## Hardware Used

- STM32F103C8T6
- HC-SR04 Ultrasonic Sensor
- SSD1306 OLED Display
- ESP32 DevKit V1
- Breadboard
- Jumper Wires

---

## Features

- Distance measurement using ultrasonic sensing
- Real-time OLED display update
- UART communication
- Sensor interfacing using STM32 HAL

---

## Working

1. STM32 triggers the HC-SR04 sensor.
2. Echo pulse duration is measured.
3. Distance is calculated.
4. Distance is displayed on the OLED.
5. Distance data is sent through UART.

---

## Skills Learned

- STM32CubeIDE
- GPIO Configuration
- UART Communication
- I2C OLED Interfacing
- Sensor Interfacing
- Embedded C Programming






