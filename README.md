# Servo with Distance Sensor

This project demonstrates how to control a servo motor based on the distance measured by an ultrasonic sensor using Arduino.

## Features
- Measures distance using an ultrasonic sensor (HC-SR04).
- Controls a servo motor to move based on distance thresholds.
- Prints distance data to the Serial Monitor.

Alternatively, download and view the video directly:
[MyArdunioProject.mp4](https://github.com/beyzaaslan/ServoWithDistanceSensor/blob/main/MyArdunioProject.mp4)

## Code
The main code for this project can be found in the repository:
[ServoWithDistanceSensor.ino](./ServoWithDistanceSensor.ino)

## How It Works
1. The ultrasonic sensor sends a sound wave and listens for its reflection.
2. The distance is calculated based on the time taken for the wave to return.
3. If the distance is less than 40 cm, the servo motor moves to 90° for 5 seconds.
4. If the distance is greater than or equal to 40 cm, the servo motor returns to its default position (0°).

## Components
- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- Servo Motor
- Jumper Wires
- Breadboard

## Circuit Diagram
You can find the circuit diagram in the repository to replicate the setup.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/beyzaaslan/ServoWithDistanceSensor.git
