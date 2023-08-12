# Arduino Color Sensor
This project uses an Arduino Uno and Adafruit TCS34725 color sensor to detect the color of objects placed in proximity. It outputs the detected color through a Python GUI.

## Hardware
* Arduino Uno
* Adafruit TCS34725 RGB color sensor module
* Breadboard
* Jumper wires
* USB cable
## Software
* Arduino IDE
* Python 3
* Tkinter Python module
* PySerial Python module
Arduino code (colorSense.ino) reads RGB values from sensor and outputs to serial.

Python GUI (arduinoLink.py) displays detected color on screen.

## Usage
1. Upload colorSense.ino to Arduino
2. Connect TCS34725 sensor to Arduino
3. Run arduinoLink.py
4. Place objects near sensor
5. Detected color is displayed on Python GUI
## Calibration
The sensor is calibrated to detect the following 11 colors:

* Black
* Blue
* Red
* Brown
* Purple
* Green
* Gray
* Orange
* Yellow
* Pink
* White
See color_chart.txt for RGB thresholds used for each color.

## Credits
Created by Wilson Neira
