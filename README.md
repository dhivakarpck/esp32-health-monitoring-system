# esp32-health-monitoring-system
Real-time health monitoring system using ESP32, MAX30102, BMA400, and classic data structures in Embedded C.

ESP32 Health Monitoring System using Embedded C and Data Structures

Overview
- Real-time health monitoring system developed using ESP32 microcontroller
- Measures heart rate, SpO2, body temperature, and motion
- Sensor data is efficiently managed using classical data structures in Embedded C

Objectives
- Monitor vital health parameters in real time
- Organize sensor data efficiently using data structures
- Develop a low-cost and portable embedded healthcare solution

System Architecture
- Sensor Layer: MAX30102 for heart rate, SpO2, and temperature, BMA400 for motion detection
- Processing Layer: ESP32 microcontroller with I2C communication
- Storage and Analysis Layer: Linked List, Queue, Stack, Binary Search Tree
- Output Layer: OLED display and Serial Monitor

Hardware Components
- ESP32 Development Board
- MAX30102 Sensor (Heart Rate, SpO2, Temperature)
- BMA400 Accelerometer
- 128x64 OLED Display (I2C)
- Breadboard and Jumper Wires

Software and Tools
- Embedded C and C++
- Arduino IDE
- I2C Communication Protocol
- Adafruit SSD1306 and GFX Libraries

Data Structures Used
- Linked List: Maintains a complete dynamic log of sensor readings
- Queue: Handles real-time data streaming in FIFO order
- Stack: Provides instant access to the most recent readings
- Binary Search Tree: Stores sensor data sorted by timestamp

Key Features
- Real-time acquisition of health and motion data
- Live visualization of sensor values on OLED display
- Efficient memory usage through dynamic data structures
- I2C bus recovery mechanism for reliable sensor communication
- Modular and scalable embedded system design

Output
- Live heart rate, SpO2, temperature, and motion data displayed on OLED
- Detailed sensor logs and sorted data output through Serial Monitor

Future Enhancements
- Cloud or mobile application integration
- Persistent data storage using SD card or flash memory
- Advanced data analytics and anomaly detection
- AI-based health trend analysis

Team Contribution
- Collaborative development involving hardware integration, sensor interfacing,
  embedded software development, testing, and documentation

Documentation
- Complete project report and technical details are available in the documentation folder

License
- MIT License for academic and educational use
