# IoT Based Patient Health Monitoring System  

This project demonstrates a real-time health monitoring system using Arduino and ESP8266. It integrates multiple sensors such as temperature, PIR motion sensor, smoke sensor, and pulse sensor, along with Bluetooth connectivity, to provide a smart health monitoring solution. The data collected is displayed locally on an LCD and uploaded to cloud platforms like ThingSpeak for remote monitoring.  

## Features  
- Measures body temperature using LM35 sensor  
- Detects motion and presence using PIR sensor  
- Monitors smoke levels for safety alerts  
- Tracks pulse rate with a pulse sensor  
- Sends and receives data via Bluetooth module for local communication  
- Wi-Fi integration with ESP8266 to upload data to ThingSpeak for real-time cloud monitoring  
- LCD display for on-spot readings  
- Alerts and visual feedback using LEDs  

## Hardware Components  
- Arduino Nano / Uno  
- ESP8266-01 Wi-Fi Module  
- LM35 Temperature Sensor  
- PIR Motion Sensor  
- Smoke Sensor  
- Pulse Sensor  
- Bluetooth Module (HC-05/HC-06)  
- 16x2 LCD Display  
- Potentiometer 10k  
- LEDs and Resistors (1k, 2k)  
- Breadboard and jumper wires  

## Software & Tools  
- Arduino IDE for coding and uploading sketches  
- ThingSpeak for IoT data visualization  
- Serial Monitor for debugging  
- Mobile Bluetooth apps for testing local communication  

## How it Works  
1. Sensors collect patient health parameters such as temperature, heart rate, motion, and smoke detection.  
2. Data is processed by Arduino and displayed on an LCD.  
3. Through the ESP8266 module, processed data is sent to ThingSpeak for cloud visualization.  
4. Bluetooth module allows short-range communication and control via smartphone.  
5. Alerts are triggered in case of abnormal readings.  

## Code & Outputs  
- Arduino code is provided for reading each sensor, sending data to ThingSpeak, and establishing Bluetooth communication.  
- Output includes real-time sensor values on LCD, ThingSpeak graphs for remote monitoring, and visual/audio alerts for critical conditions.  

## Applications  
- Remote patient health monitoring for hospitals and homes  
- Early detection of unsafe conditions such as smoke or unusual activity  
- Portable IoT device for continuous health tracking  
- Implement machine learning for predictive health analytics  
- Deploy on a permanent server or cloud for scalability  
