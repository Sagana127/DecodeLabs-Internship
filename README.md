# DecodeLabs-Internship
# Internet of Things (IoT) Projects

## Overview

This repository contains a collection of Internet of Things (IoT) projects developed using the ESP32 microcontroller as part of my learning in embedded systems and IoT application development. These projects demonstrate practical implementations of sensor interfacing, automation, cloud connectivity, interrupt handling, and real-time monitoring. Each project is designed to solve a real-world problem while providing hands-on experience with IoT hardware, embedded programming, and communication protocols.

## Projects

### Project 1 – Smart Environmental Monitor

The Smart Environmental Monitor is an ESP32-based system that measures temperature and humidity using the DHT22 sensor. The project implements both blocking (`delay()`) and non-blocking (`millis()`) programming techniques to periodically acquire sensor data. The measured values are displayed on the Serial Monitor as well as on an I2C LCD, demonstrating efficient real-time environmental monitoring.

### Project 2 – Automated Irrigation Controller

This project implements an automated irrigation system using an ESP32, soil moisture sensor, and relay module. The system continuously monitors soil moisture levels and automatically controls a water pump based on predefined moisture thresholds. Hysteresis logic is incorporated to ensure stable relay operation and prevent unnecessary switching, making the system suitable for smart agriculture applications.

### Project 3 – Cloud-Connected Security Node

The Cloud-Connected Security Node uses an ESP32 and an HC-SR04 ultrasonic sensor to monitor the distance of nearby objects. The measured data is transmitted to the Adafruit IO cloud platform using the MQTT protocol, enabling real-time remote monitoring. The system also identifies potential intrusions based on distance measurements, demonstrating cloud-enabled IoT telemetry.

### Project 4 – Edge-Computing Smart Home Appliance

This project presents an edge-computing smart home safety system that integrates a PIR motion sensor, gas sensor, LEDs, buzzer, and LCD with an ESP32. Hardware interrupts are used for immediate motion detection, while gas concentration is continuously monitored to activate emergency alerts whenever unsafe conditions are detected. The project demonstrates real-time embedded processing and fail-safe operation for smart home environments.

## Technologies Used

- ESP32 Development Board
- Arduino IDE
- Embedded C/C++
- DHT22 Temperature & Humidity Sensor
- Soil Moisture Sensor
- HC-SR04 Ultrasonic Sensor
- PIR Motion Sensor
- Gas Sensor
- Relay Module
- I2C LCD Display
- MQTT Protocol
- Adafruit IO Cloud Platform

## Author

**Sagana Y**
