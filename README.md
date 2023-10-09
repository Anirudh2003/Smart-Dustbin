---

# Smart Dustbin

This repository contains an Arduino project that demonstrates how to use IOT components to build a smart dustbin.

## Components Used
- Arduino board (e.g., Arduino Uno)
- Ultrasonic Sensors (HC-SR04)
- Servo Motor
- Jumper Wires
- Dustbin
- Buzzer

## Wiring Instructions
1. Connect the TRIG pin of the ultrasonic sensor to Arduino pin 6.
2. Connect the ECHO pin of the ultrasonic sensor to Arduino pin 7.
3. Connect the control pin of the servo motor to Arduino pin 9.

## How It Works
The ultrasonic sensor measures the distance to an object. If the distance is less than the threshold (50 centimeters in this example), the servo motor rotates to 90 degrees. Otherwise, the servo motor rotates to 0 degrees. The measured distance is printed to the Serial Monitor.

## Setup
1. Connect the components as per the wiring instructions.
2. Upload the provided Arduino sketch (`ultrasonic_servo.ino`) to your Arduino board.
3. Open the Serial Monitor at a baud rate of 9600 to see the measured distance.

##Work in Progress
We are planning to connect it to an app through Blynk to make it commercially viable for large enterprises to centralize their waste management.

---

