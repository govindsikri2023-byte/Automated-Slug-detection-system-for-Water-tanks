# Automated Sludge Detection System for Water Tanks

## Overview

This project presents an Arduino-based automated sludge detection system designed to monitor sludge accumulation in water tanks.

Since Tinkercad does not provide a turbidity sensor, a potentiometer is used to emulate the analog output of the sensor.

The system continuously reads the simulated sludge level and alerts the user through LEDs, a buzzer, and a 16×2 LCD display.

---

## Features

- Continuous sludge monitoring
- LCD status display
- Green LED for clean tank
- Red LED for high sludge
- Audible buzzer alert
- Low-cost prototype
- Easily expandable for IoT

---

## Hardware

- Arduino Uno
- LCD 16×2
- Potentiometer (Sensor Simulation)
- LEDs
- Piezo Buzzer

---

## Software

- Arduino IDE
- Tinkercad
- Fritzing

---

## Working Principle

The potentiometer simulates the analog output of a turbidity sensor.

The Arduino reads the analog value.

Depending on predefined thresholds:

- Clean → Green LED
- Warning → LCD Warning
- High Sludge → Red LED + Buzzer

---

## Future Enhancements

- Real Turbidity Sensor
- ESP32 WiFi Monitoring
- Mobile App Notifications
- Cloud Logging
- Automatic Tank Cleaning
