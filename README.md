# I.I.T-AT1-Pet_Feeder_Project
This repository is for Intro to Information Technology - Assessment Task 1 - The Automated Pet Feeder Project. In this repository will include folders for different sections of the assignment with their appropriate files within them for marking.


# Automatic Pet Feeder Project

## Project Overview
This project is an automated pet feeding system designed to dispense food to pets at scheduled times. It monitors feeder capacity, logs events, alerts staff when necessary, and tracks food consumption to ensure pets are eating properly. The system is designed to operate continuously and autonomously using real-time logic and sensor feedback.

## Features
- Scheduled feeding times for different pets (e.g., dogs and cats)
- Real-time clock (RTC) integration for time-based operations
- Servo motor control for precise food dispensing
- Feeder capacity monitoring with alert system
- Food consumption tracking using bowl weight measurement
- Logging of successful and failed operations
- Staff alert system for refill and error handling
- Continuous operation with CPU-friendly loop management

## Hardware Components
- Microcontroller (Arduino Uno or Raspberry Pi)
- RTC Module (e.g., DS3231)
- Servo Motor
- Load Cell with HX711 Amplifier
- Ultrasonic or IR Sensor for feeder capacity
- LCD Display or LEDs for status indication
- Buzzer for audible alerts
- Wi-Fi Module (ESP8266 or built-in Raspberry Pi)
- Power Supply (Battery or Wall Adapter)
- Push Button for manual override

## Setup Instructions
1. Assemble the hardware components as per the circuit diagram.
2. Connect the sensors and actuators to the microcontroller GPIO pins.
3. Upload the control logic code to the microcontroller.
4. Configure the RTC module with the correct time.
5. Calibrate the load cell for accurate weight measurement.
6. Power on the system and verify all components are functioning.

## Usage
- The system checks feeder capacity continuously and alerts staff if refill is needed.
- At scheduled times (08:00, 08:30, 18:00, 18:30), it dispenses food based on the pet type.
- After dispensing, it waits 15 minutes and measures bowl weight to confirm consumption.
- Logs are maintained for all operations, and alerts are sent in case of issues.

## Future Improvements
- Integration with a mobile app for remote monitoring and control
- Camera module for visual pet monitoring
- Voice assistant compatibility (e.g., Alexa, Google Assistant)
- Battery backup for power outages
- Micro Digital Circuit Display
- Enhanced error handling and retry logic

---

For questions or contributions, please contact Abdullah Rubbani (u3280268).
