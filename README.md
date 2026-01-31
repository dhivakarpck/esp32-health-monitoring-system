# esp32-health-monitoring-system
Real-time health monitoring system using ESP32, MAX30102, BMA400, and classic data structures in Embedded C.

ESP32 Health Monitoring System using Embedded C & Data Structures

Overview
This project implements a real-time health monitoring system using the ESP32 microcontroller. It measures vital parameters such as heart rate, SpO₂, body temperature, and motion, and efficiently manages sensor data using classical data structures implemented in Embedded C.

Objectives

Real-time monitoring of vital health parameters

Efficient organization of sensor data using data structures

Development of a low-cost, portable embedded healthcare solution

System Architecture
The system is designed using a modular layered approach:

Sensor Layer: MAX30102 for heart rate, SpO₂, temperature and BMA400 for motion detection

Processing Layer: ESP32 microcontroller with I2C communication

Storage and Analysis Layer: Linked List, Queue, Stack, and Binary Search Tree

Output Layer: OLED display and Serial Monitor

Hardware Components

ESP32 Development Board

MAX30102 Sensor (Heart Rate, SpO₂, Temperature)

BMA400 Accelerometer

128x64 OLED Display (I2C)

Breadboard and Jumper Wires

Software and Tools

Embedded C / C++

Arduino IDE

I2C Communication Protocol

Adafruit SSD1306 and GFX Libraries

Data Structures Used
Linked List
Used to maintain a complete log of all sensor readings dynamically.

Queue
Used for real-time data streaming in First-In-First-Out order.

Stack
Used for instant access to the most recent sensor readings.

Binary Search Tree (BST)
Used for storing and retrieving sensor data sorted by timestamp.

Key Features

Real-time acquisition of health and motion data

Live visualization of sensor values on OLED display

Efficient memory usage using dynamic data structures

I2C bus recovery mechanism for reliable communication

Modular and scalable embedded system design

Output

Live display of heart rate, SpO₂, temperature, and motion data on OLED

Detailed sensor logs and sorted data output via Serial Monitor

Future Enhancements

Cloud or mobile application integration

Persistent data storage using SD card or flash memory

Advanced data analytics and anomaly detection

AI-based health trend analysis

Team Contribution
The project was developed through collaborative effort, involving hardware integration, sensor interfacing, embedded software development, testing, and documentation.

Documentation
The complete project report and technical details are available in the documentation folder.

License
This project is licensed under the MIT License and is intended for academic and educational use.
