# Arduino Distance Measurement System

This project measures distance using an HC-SR04 ultrasonic sensor and displays the output on an I2C LCD.
A buzzer is used to give an alert when an object comes within a predefined distance.

## Components Used
- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- I2C LCD (16x2)
- Buzzer
- Breadboard & Jumper Wires

## Working
The ultrasonic sensor sends a trigger pulse and receives the echo signal.
The time difference is used to calculate distance.
The calculated distance is displayed on the LCD.
When the distance goes below a set threshold, the buzzer turns ON as a warning alert.

## Applications
- Obstacle detection systems
- Parking assistance
- Basic robotics
- Safety alert systems

