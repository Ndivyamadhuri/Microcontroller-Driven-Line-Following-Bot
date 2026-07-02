# Microcontroller-Driven Line Following Bot

## Overview

This project implements a microcontroller-based autonomous line following robot capable of navigating a predefined path using infrared (IR) sensors. The robot continuously detects the line using IR sensors, while the Arduino Uno (ATmega328P microcontroller) processes the sensor data and controls the motors through an L298N motor driver. The system demonstrates the practical implementation of embedded systems, sensor interfacing, and autonomous robotic navigation.

---

## Features

- Autonomous line following
- Real-time path detection using IR sensors
- Arduino Uno based embedded control
- Motor control using L298N motor driver
- Differential steering for left and right turns
- Stable navigation on predefined paths

---

## Components Used

- Arduino Uno (ATmega328P Microcontroller)
- IR Sensors
- L298N Motor Driver
- DC Motors
- Robot Chassis
- 12V Battery

---

## Working Principle

1. IR sensors continuously detect the black line.
2. Sensor outputs are sent to the Arduino Uno.
3. The microcontroller processes the sensor data.
4. Control signals are sent to the L298N motor driver.
5. The motor driver drives the DC motors to move the robot forward or adjust its direction.
6. The process repeats continuously to ensure accurate line tracking.

---

## Results

The robot successfully follows the predefined path by continuously monitoring the line using IR sensors. Based on the sensor inputs, the Arduino Uno controls the DC motors through the L298N motor driver to maintain the correct direction. The robot automatically adjusts its movement whenever it deviates from the path, demonstrating reliable autonomous navigation and effective embedded control.

---

## Tools Used

- Arduino IDE
- Arduino Uno (ATmega328P)
