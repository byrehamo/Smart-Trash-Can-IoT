# Smart Trash Can with Blynk Integration ♻️

## About the Project
This project is an IoT-based smart trash can designed to improve hygiene and convenience through automatic lid control, environmental monitoring, and remote control.

Developed as a group project for ITE233 – Introduction to Internet of Things at Stamford International University.

## Features
- Automatic lid opening using an ultrasonic sensor
- Servo motor control for opening and closing the lid
- Temperature and humidity monitoring
- Real-time information displayed on an LCD screen
- Remote monitoring through the Blynk mobile application
- Manual lid control through Blynk
- Real-time sensor data monitoring

## Hardware Components
- ESP32 Microcontroller
- HC-SR04 Ultrasonic Sensor
- DHT11 Temperature and Humidity Sensor
- SG90 Micro Servo Motor
- 16x2 I2C LCD Display
- Breadboard and jumper wires

## Software & Technologies
- Arduino IDE
- C/C++ (Arduino programming)
- ESP32
- Blynk IoT Platform
- Wi-Fi / IoT Communication

## How It Works
1. The ultrasonic sensor detects an object near the trash can.
2. The ESP32 processes the sensor reading.
3. The servo motor automatically opens the lid.
4. The lid closes when the object moves away.
5. The DHT11 sensor measures temperature and humidity.
6. Sensor readings and lid status are displayed on the LCD.
7. Data is sent to the Blynk application for remote monitoring and control.

## Project Report
The full project report includes the system design, hardware connections, Arduino implementation, Blynk setup, and project outcomes.

## Course
ITE233 – Introduction to Internet of Things

Stamford International University

Term 1/2025

## Project Type
University Group Project
