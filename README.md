# Reaction Time Tester

## Description
This project is a reaction time tester built on the Arduino platform. The system uses an LCD screen to display instructions and results, a red LED as a visual signal, and a pushbutton to record the user's reaction. When the LED lights up, the user must press the button as quickly as possible, and the resulting time is displayed on the screen.

## Hardware Components
Based on the schematic, you will need the following items:
* 1x Arduino Uno board
* 1x Breadboard
* 1x LCD Screen (16x2)
* 1x Potentiometer (used to adjust the LCD screen contrast)
* 1x Red LED
* 1x Pushbutton
* 2x Resistors (one for LED protection and one for the LCD backlight)
* Jumper wires

## Hardware Connections
The wiring diagram shows the following main connections to the Arduino board:

**LCD Screen:**
* The RS pin is connected to digital pin 12.
* The E (Enable) pin is connected to digital pin 11.
* Data pins D4, D5, D6, and D7 are connected to digital pins 5, 4, 3, and 2, respectively.
* Contrast (V0) is adjusted via the center pin of the potentiometer.

**User Interface (I/O):**
* The **Red LED** is connected to digital pin 8 (through a resistor).
* The **Pushbutton** is connected to digital pin 9.

**Power:**
* The components on the breadboard are powered by the 5V and GND pins of the Arduino board.
