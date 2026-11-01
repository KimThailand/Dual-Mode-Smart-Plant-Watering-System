# Dual-Mode Smart Plant Watering System

An automatic and manual plant watering system using Arduino Uno and a soil moisture sensor.

## Project Overview

This project uses a soil moisture sensor to monitor soil conditions and control a water pump through a relay module. It supports two operating modes: Automatic Mode, which waters plants when the soil is dry, and Manual Mode, which allows users to control the pump using a push button.

## Features

- Automatic watering based on soil moisture levels.
- Manual pump control using a push button.
- Mode switching between Automatic and Manual.
- Relay module control for the water pump.
- Soil moisture monitoring via Serial Monitor.
- Button debouncing to prevent repeated inputs.

## Hardware Components

- Arduino Uno
- Soil Moisture Sensor
- Relay Module (Active LOW)
- Water Pump
- Push Buttons
- Connecting Wires

## Software & Tools

- Arduino IDE
- C/C++ (Arduino Programming)

## System Operation

**Automatic Mode**
- Reads soil moisture values from the sensor.
- Turns ON the pump when soil moisture value is above 700.
- Turns OFF the pump when soil moisture value is below 300.

**Manual Mode**
- Allows users to turn the water pump ON or OFF using a push button.

## Project Images

Add project simulation or hardware images here.

## Learning Outcomes

- Arduino programming and digital/analog I/O.
- Soil moisture sensor integration.
- Relay and water pump control.
- Automatic and manual control systems.
- Basic embedded systems development.

## Author

**Pakorn Kaewmanee**

Computer Engineering Student

Rajamangala University of Technology Phra Nakhon

## Project Category

IoT | Embedded Systems | Arduino
