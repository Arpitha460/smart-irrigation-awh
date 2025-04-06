## smart-irrigation-awh

Smart Irrigation System using Atmospheric Water Harvesting and AI-Powered Automation

## Problem Statement

Water scarcity and inefficient irrigation are major issues in agriculture. Traditional systems fail to adapt to changing climate conditions and often waste water.

## Solution Overview

Our system combines Atmospheric Water Harvesting (AWH) with AI-based automation to deliver a smart, sustainable irrigation solution. It uses real-time sensor data to optimize water usage, ensuring crops receive the right amount at the right time.

## Architecture

![architecture png](https://github.com/user-attachments/assets/3152c770-b48e-4305-91a5-f4249d68da51)


## Features

- Atmospheric Water Harvesting (AWH)
- Solar-Powered Operation
- Automatic Filtration System
- AI Integration
- Soil Moisture Sensors
- Automated Sprinkler System
- Sustainable and Eco-Friendly
- Minimal Human Intervention
- Real-time Monitoring
- Scalable Design

## Tech Stack

### Hardware & IoT
- *ESP32 / ESP8266* – Microcontroller for edge computing and sensor integration  
- *Sensors* – Soil moisture, temperature, water level  
- *Vacuum Chamber Components* – For atmospheric water harvesting  
- *Solar Panels* – For power supply  
- *Relay Module* – For controlling pumps and sprinklers  
- *Wireless Communication* – LoRa, Wi-Fi, or Bluetooth

### Embedded Systems & Firmware
- *ESPHome* – Simple YAML-based firmware for ESP devices  
- *Arduino IDE* – Custom embedded programming  
- *Node-RED* – Visual flow-based development for IoT integration

### AI & Machine Learning
- *TensorFlow Lite* – On-device machine learning predictions  
- *Scikit-learn* – Predictive modeling for irrigation schedules  
- *OpenCV* – Optional plant health image analysis  
- *Hugging Face Transformers* – Conversational AI assistant (text/voice-based)

### Cloud & Backend (Optional)
- *InfluxDB* – Time-series data storage  
- *Grafana* – Real-time dashboard and analytics  
- *Firebase / AWS / Local Server* – Remote access and data storage  
- *OpenWeatherMap API* – Weather-based planning and insights

### Mobile & Web
- *Blynk (Open Source)* – Mobile dashboard for control and monitoring  
- *React.js / Flutter* – (Optional) Custom user interfaces  
- *MQTT Protocol* – Lightweight communication protocol for IoT devices


## Team

EcoFlow  
Led by Arpitha Reddy B J, Pallavi K, Manu S N.
Team of student innovators passionate about smart agriculture and sustainability.

## How to Run the Project

### 1. Hardware Setup
- Connect ESP32/ESP8266 to sensors (soil moisture, temperature, etc.)
- Install solar panel and battery connections
- Set up relay modules to control sprinklers and vacuum chamber
- Integrate water filtration and atmospheric water harvesting components

### 2. Firmware Installation
- Flash ESPHome or Arduino sketch onto ESP microcontrollers
- Use [ESPHome Dashboard](https://esphome.io/) or Arduino IDE for deployment

### 3. Backend and Dashboard
- Set up InfluxDB and Grafana for real-time data visualization
- (Optional) Deploy Node-RED for flow-based control of IoT devices
- Configure OpenWeatherMap API for weather integration

### 4. Mobile Dashboard (Optional)
- Use Blynk app (open-source version) to remotely control and monitor sensors
- Customize widgets for soil moisture, temperature, pump control, etc.

### 5. AI & ML Integration
- Deploy trained TensorFlow Lite/Scikit-learn models to ESP for on-device predictions
- Use Node-RED or local server to integrate AI decisions into the control system
- (Optional) Add Hugging Face assistant for voice/text control interface

### 6. Testing & Deployment
- Test sensor readings on dashboard
- Verify automatic and manual irrigation triggering
- Ensure water collection, purification, and control modules work properly

> *Note:* All configurations and credentials should be stored in a secrets.yaml or .env file to maintain security.

## License

This project is currently not licensed.
This project is submitted for Pragati AI Hackathon 2025.
