# Dual-Axis Solar Tracker Using Arduino
Dual-Axis Solar Tracker is a project that optimizes the energy output of solar panels by aligning them to face the sun directly throughout the day. The system rotates the solar panels both horizontally and vertically to ensure maximum exposure to sunlight, thereby maximizing energy generation. The tracker uses Light Dependent Resistors (LDRs) to detect the direction of the sun and adjusts the panel accordingly using servo motors.

## Motivation Behind the Project
Solar panels are most efficient when sunlight falls directly on them. However, the sun's position changes throughout the day, which leads to reduced energy efficiency if the panels are stationary. This project was created to solve this problem by automatically adjusting the solar panels to track the sun's position on both horizontal and vertical axes, ensuring that sunlight always hits the panels at a perpendicular angle.

## How It Works
The system employs four LDR sensors placed at the edges of the solar panel. The difference in light intensity captured by these sensors determines the movement of two servo motors that control the horizontal and vertical positions of the panel. By constantly adjusting the panel, the system keeps it aligned with the sun to generate maximum energy.

## Horizontal Tracking
The bottom servo controls the horizontal axis of the panel. It adjusts the panel’s position to follow the sun from east to west.

## Vertical Tracking
The top servo controls the vertical axis of the panel. It adjusts the panel to maintain an optimal angle with the sun as it rises and sets.

## Hardware Requirements
Arduino Uno: The microcontroller that processes sensor input and controls the servo motors.
LDRs (Light Dependent Resistors): Detect sunlight intensity from four different directions.
Servo Motors: Control the horizontal and vertical movement of the solar panel.
Breadboard: For easy circuit connections.
Jumper Wires: To connect components to the Arduino.
Resistors: To work with the LDRs.

## Pin Configuration
### LDRs:
Top Right LDR (A1)
Top Left LDR (A2)
Bottom Right LDR (A0)
Bottom Left LDR (A3)

### Servo Motors:
Horizontal Servo: Connected to pin 10.
Vertical Servo: Connected to pin 9.

## Required Libraries
Servo.h: Standard Arduino library for controlling servo motors.

## Setting Up
Assemble the Circuit: Connect the four LDRs and the two servos to the Arduino according to the pin configuration above.
Upload Code: Open the Arduino IDE, copy and paste the code, and upload it to the Arduino.
Test the System: Once everything is connected, place the system in sunlight or use a torch to simulate sunlight. The panel should start moving to align with the light source.

## Features
Real-Time Sun Tracking: Automatically adjusts solar panel position based on light intensity from four directions.
Dual-Axis Control: The system tracks both horizontally and vertically to optimize energy output.
Adjustable Servo Limits: You can customize the range of movement for both the horizontal and vertical axes based on your panel's needs.


![image](https://github.com/pratz222/Dual-Axis-Solar-Tracker-using-Arduino/assets/53640877/b22b38a2-95ec-4394-9192-b06cb582d816)

## Contribution
Contributions to the Dual-Axis Solar Tracker project are welcome! Feel free to report issues, suggest enhancements, or submit pull requests to help improve this solar tracking system. Let’s work together to create a more efficient solar energy solution!
