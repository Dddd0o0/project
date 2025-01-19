# Overview

The project aims to design and develop an advanced smart system for managing parking gate operations, utilizing sensing technologies and automation to enhance user experience and improve safety. The system detects the approach of vehicles near the gate using precise sensors, triggering the gate to open automatically, facilitating entry or exit without the need for human intervention.


Main objectives of the Parking systems :
 1. Improving parking management and organizing vehicle entry and exit processes.
 2. Increasing operational efficiency through system automation.
 3. Enhancing user experience by providing simple and fast solutions.
 4. Strengthening security and safety through advanced monitoring systems.


Main Features :

1. Distance Measurement Between the Car and the Obstacle.

2. Alerting the Driver When Approaching the Obstacle Too Closely.

3. Automatically Lifting the Barrier When the Car Approaches.

Sub Features :

1. System Settings Adjustment.

2. Low Power Consumption.

3. Environmental Compatibility.


How it Works:
- The system tracks the number of available parking slots.
- When a car enters (IR1 sensor is triggered), the parking slot decreases and the gate opens.
- When a car exits (IR2 sensor is triggered), the parking slot increases and the gate closes.
- The number of available slots is displayed on the LCD.

3. Project Requirement :
 
HardWare :
1. Arduino UNO.
2. Jumper wires.
3. Breadboard.
4. LCD Display with l2C Module.
5. Servo Motor.
6. IR Sensor.

Software :
1. Visual Studio software programing language C++