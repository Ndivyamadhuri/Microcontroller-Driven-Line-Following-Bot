# Microcontroller-Driven Line Following Bot

## Overview

This project presents a microcontroller-based autonomous line following robot designed to detect and follow a predefined path using infrared (IR) sensors. The microcontroller continuously monitors the sensor outputs and processes the received data to determine the robot's direction. Based on the sensor feedback, it sends control signals to the L293D motor driver, which drives the DC motors to move the robot forward or adjust its direction by turning left or right. The system demonstrates reliable autonomous navigation and practical implementation of embedded control systems.

---

## Features

- Autonomous line detection and tracking
- Real-time navigation using IR sensors
- Microcontroller-based embedded control
- DC motor control using L293D motor driver
- Reliable path following with continuous sensor feedback
- Compact and efficient robotic system

---

## Components Used

- Arduino Uno (ATmega328P Microcontroller)
- IR Sensors
- L293D Motor Driver
- DC Motors
- Robot Chassis
- Battery Supply

---

## Working Principle

1. The IR sensors continuously detect the black line on the surface.
2. The sensor outputs are sent to the Arduino Uno (ATmega328P microcontroller).
3. The microcontroller processes the sensor inputs in real time.
4. Based on the detected path, control signals are generated for the L293D motor driver.
5. The motor driver controls the DC motors, enabling the robot to move forward or change direction.
6. The robot continuously repeats this process to accurately follow the line.

---

## Results

The robot successfully follows the predefined path by continuously detecting the line using IR sensors. The microcontroller processes the sensor inputs in real time and controls the DC motors through the L293D motor driver to maintain the correct path. When the robot deviates from the line, it automatically adjusts its direction by turning left or right until it realigns with the path. The implementation demonstrates effective sensor interfacing, embedded control, and motor control for autonomous navigation.

---

## Tools Used

- Arduino IDE
- Arduino Uno (ATmega328P Microcontroller)

---

## Repository Structure

```
Microcontroller-Driven-Line-Following-Bot
│
├── README.md
├── Images
│   ├── Robot.jpg
│   ├── Circuit_Diagram.png
│   └── Hardware_Setup.jpg
│
└── Results
    ├── Output.png
    └── Working_Demo.mp4 (Optional)
```
