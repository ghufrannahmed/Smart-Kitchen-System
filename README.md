# Smart-Kitchen-System
Smart Kitchen System
The Smart Kitchen System is an Arduino-based project designed to enhance safety in kitchens by monitoring LPG cylinder levels, detecting gas leaks, and identifying fire hazards. This system ensures early alerts to prevent accidents and maintain a safe cooking environment.

Features
LPG Weight Monitoring:

Measures the remaining gas in the cylinder using a load cell and HX711 driver.
Displays the weight on a 16x2 LCD in real-time.
Gas Leakage Detection:

Monitors air quality using an MQ135 gas sensor.
Alerts with a buzzer, turns on an exhaust fan, and opens a window using a motor if leakage is detected.
Fire Detection:

Uses a flame sensor to detect fire hazards.
Triggers an alarm and ventilation system in case of fire.
Integrated Display:

A user-friendly LCD interface for real-time updates on system status.
Components
Arduino Uno: Microcontroller for processing sensor data.
MQ135 Gas Sensor: Detects LPG and other harmful gases.
Flame Sensor: Detects fire or flames.
Load Cell with HX711 Driver: Measures the weight of the LPG cylinder.
16x2 LCD: Displays real-time data and alerts.
Buzzer: Provides an audio alert for emergencies.
12V DC Motor and Fan: Activates for ventilation in case of gas leakage or fire.
Circuit Diagram
(Provide your schematic diagram or link to a diagram file here)

Code Explanation
The project is implemented using Arduino C/C++. Key functionalities include:

Sensor Data Reading: Gas sensor, flame sensor, and load cell readings.
Alerts and Actions: Triggering buzzers, fans, and motors upon detection of hazards.
Real-time Updates: Displaying gas weight and alerts on an LCD.
How to Use
Connect the components as per the circuit diagram.
Upload the provided code to the Arduino Uno using the Arduino IDE.
Power on the system and observe the real-time updates on the LCD.
Test the system with simulated gas leaks and flames to verify functionality.
Future Scope
Add IoT capabilities to send alerts to smartphones.
Incorporate pressure sensors for pipe monitoring.
Enhance display and user interface with touchscreens.
