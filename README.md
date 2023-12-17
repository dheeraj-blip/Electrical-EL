Home Automation System with Servo Motors, Arduino, LDR, and Bulbs
Overview
This project is a home automation system that utilizes Arduino, two servo motors, an LDR (Light Dependent Resistor), and bulbs to create a smart lighting solution. The system allows users to control the intensity and direction of light in a room through a simple and efficient setup.

Features
Servo Motor Control: The system incorporates two servo motors that control the movement of the bulbs horizontally and vertically. This enables users to precisely adjust the direction of light in the room.

LDR Sensor Integration: An LDR sensor is used to detect the ambient light level in the room. The system can automatically adjust the brightness of the bulbs based on the environmental lighting conditions, providing an energy-efficient solution.

Arduino-Based Control: The project is built on the Arduino platform, making it easy to program and customize. Users can implement additional features and integrate the system with other smart home devices.

Components
Arduino Board
2 x Servo Motors
LDR (Light Dependent Resistor)
Bulbs (LED or other types)
Breadboard and Jumper Wires
Power Supply for Servo Motors and Bulbs
Setup
Connect Servo Motors: Attach the servo motors to the Arduino board. Connect the control wires to specified digital pins on the Arduino.

Connect LDR: Connect the LDR to an analog pin on the Arduino. Use a resistor in a voltage divider configuration to create a voltage signal corresponding to the light intensity.

Connect Bulbs: Connect the bulbs to the power supply, ensuring proper polarity. Connect the power supply to the Arduino and ensure that it can provide enough power for both the Arduino and the servo motors.

Upload Arduino Code: Upload the provided Arduino code to the board. This code includes logic for servo motor control based on user input and LDR sensor readings.

Calibration: Calibrate the system by adjusting the servo motor angles and LDR sensitivity to suit the room's layout and lighting conditions.

Usage
Manual Control: Use external controls, such as buttons or a smartphone app, to manually adjust the orientation of the bulbs.

Automatic Mode: Enable the automatic mode for the system to adjust the brightness of the bulbs based on ambient light conditions detected by the LDR sensor.

Integration with Smart Home Systems: Extend the project by integrating it with popular smart home platforms, enabling users to control the lighting system through voice commands or automation routines.
