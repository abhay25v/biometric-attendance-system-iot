# Smart Biometric Attendance System using ESP8266

This repository contains the source code and documentation for the Smart Biometric Attendance System using ESP8266. The project is designed to utilize biometric data for attendance management efficiently and securely.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to create a biometric attendance system using the ESP8266 microcontroller. The system captures biometric data, processes it, and logs attendance in a database.

## Features
- Reliable biometric data capture
- Real-time data processing
- Attendance logging
- User-friendly interface
- Secure storage of biometric data

## Hardware Requirements
- ESP8266 microcontroller
- Biometric sensor (R307)
- Power supply
- Connecting cables
- OLED Display 0.96 inch

## Software Requirements
- Arduino IDE
- PHP Server (e.g., XAMPP)
- MySQL Database

## Installation
### Arduino IDE Setup
1. Install the Arduino IDE from [Arduino's official website](https://www.arduino.cc/en/software).
2. Install the ESP8266 board package through the Arduino IDE's Board Manager.
3. Clone this repository to your local machine.
4. Open the project files in the Arduino IDE.
5. Upload the code to the ESP8266 microcontroller.

### PHP Server Setup
1. Install a PHP server like XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).
2. Start the Apache and MySQL services.
3. Clone this repository to your server's root directory (e.g., `C:\xampp\htdocs` for XAMPP).
4. Import the provided SQL file into your MySQL database.

## Usage
1. Power on the ESP8266 microcontroller and connect it to your local WiFi network.
2. Open the web interface provided by the PHP server.
3. Register users by capturing their biometric data.
4. Use the biometric sensor to log attendance.

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any improvements or bug fixes.
