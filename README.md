# Line Following and Obstacle Avoidance Robot 🚗🤖

Our first robotics project where we built a robot that can **follow a line and avoid obstacles** using Arduino.  
The robot follows a path using IR sensors and stops or changes direction if an obstacle is detected within **20 cm** using an ultrasonic sensor.  
We also added extra features to make it more flexible and intelligent.

## Features
- Line following using IR sensors
- Obstacle avoidance up to 20 cm (HC-SR04 ultrasonic sensor)
- Speed control on turns using PWM

## Components Used
- Arduino Uno
- L298N Motor Driver
- DC Motors with Wheels
- IR Sensors
- Ultrasonic Sensor (HC-SR04)
- Servo Motor
- HC-05 / ESP8266 / ESP32 (optional for wireless control)
- Power Supply & Battery

## How It Works
- **IR sensors** detect the line and send signals to Arduino.  
- **Arduino** processes the data and controls the motors through L298N driver.  
- **Ultrasonic sensor** checks for obstacles within 20 cm and prevents collision.  
- **PWM** adjusts motor speed for smooth turning.

## Circuit Diagram
![Circuit Diagram]

## Future Improvements
- Adaptive line following using machine learning  
- IoT integration for live tracking and monitoring  
- Advanced path planning algorithms  

## Team Members
- **Md Manowar Alam** (Team Leader)  
- Alok Kumar Ravi  
- Md Nadeem  
- Divyanka Kumari
- Swati Singh
