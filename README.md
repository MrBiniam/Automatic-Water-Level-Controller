Automatic Water Level Controller
Project Overview
The Automatic Water Level Controller is an Arduino-based system that uses an ultrasonic sensor to measure water levels in a tank. 
It controls a pump to maintain the water level within desired limits. The LCD display shows the current water level, and a relay controls the pump.
The Project
![water level controller 1](https://github.com/user-attachments/assets/334dbfb3-4100-4278-9a29-14141bf65092)
![water level controller 2](https://github.com/user-attachments/assets/e9f9ff58-3d57-4e02-b2a0-594fd5eaaece)


Components Used:
  Arduino Uno
  LCD 1602
  Ultrasonic Sensor (HC-SR04)
  Relay Module
  Push Button
  Slide Switch
Libraries Used:
 LiquidCrystal: To interface with the LCD.
Connections:
The ultrasonic sensor measures the water level and communicates with the Arduino.
The LCD displays the water level.
A relay controls the pump.
A push button turns the system on/off, and a slide switch can be used for manual control.
How It Works:
The system measures the water level using an ultrasonic sensor. When the water reaches a predefined high level, 
the pump is turned off. If the water level goes below the threshold, the pump is turned on.

How to Run the Project:
Clone the repository:
git clone https://github.com/yourusername/Automatic-Water-Level-Controller.git
Open the project in the Arduino IDE.
Upload the code to your Arduino Uno.
Watch the system automatically control the water level.
