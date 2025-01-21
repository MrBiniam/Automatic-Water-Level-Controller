# Automatic Water Level Controller

## Project Overview
The **Automatic Water Level Controller** is an Arduino-based system designed to maintain the water level within desired limits in a water tank. The system uses an ultrasonic sensor to measure the water level, controls a pump via a relay, and displays the current water level on an LCD. Additionally, a push button allows the system to be turned on or off, and a slide switch enables manual control.

![water level controller 1](https://github.com/user-attachments/assets/334dbfb3-4100-4278-9a29-14141bf65092)
![water level controller 2](https://github.com/user-attachments/assets/e9f9ff58-3d57-4e02-b2a0-594fd5eaaece)


---

## Components Used
- **Arduino Uno**
- **LCD 1602**
- **Ultrasonic Sensor (HC-SR04)**
- **Relay Module**
- **Push Button**
- **Slide Switch**

---

## Libraries Used
- **LiquidCrystal**: To interface with the LCD and display the water level.

---

## Connections
- **Ultrasonic Sensor**: Measures the water level and communicates the data to the Arduino.
- **LCD Display**: Shows the current water level.
- **Relay**: Controls the pump based on water level thresholds.
- **Push Button**: Turns the system on and off.
- **Slide Switch**: Provides manual control for the system.

---

## How It Works
1. The ultrasonic sensor measures the water level.
2. When the water reaches a predefined high level, the pump is turned off.
3. If the water level falls below a threshold, the pump is turned on.
4. The LCD displays the current water level for the user.
5. The push button can be used to turn the system on/off, while the slide switch allows manual control.

---

## How to Run the Project

### Clone the repository:
Clone this repository to your local machine using Git:

```bash
git clone https://github.com/yourusername/Automatic-Water-Level-Controller.git

```
### Open the project in the Arduino IDE:
Open the `.ino` file in the Arduino IDE after cloning the repository.

### Upload to your Arduino Uno:
1. Connect the Arduino Uno to your computer.
2. Select the correct board and port in the **Tools** menu.
3. Click **Upload** to flash the code to the Arduino Uno.

### Watch the system in action:
The system will automatically control the water level in your tank, turning the pump on and off based on the measured water level.

---

## Contributions
Feel free to contribute to this project! You can submit a pull request with improvements, bug fixes, or new features.

---

## License
This project is licensed under the **MIT License**.

