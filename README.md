# Ultrasonic Distance Measurement with Arduino and LCD Display

## Aim
Implement a distance measurement system using Ultrasonic sensors with LED indication and display the measured distance on an LCD.

## Objectives
1. Measure the distance using an Ultrasonic sensor.
2. Display the measured distance on an LCD.

## Components Required
1. Arduino Board
2. USB Cable
3. Ultrasonic Sensor
4. Jumper Wires
5. LCD Display

## Setup Steps

1. **Connect Ultrasonic Sensor:**
   - Connect the VCC pin of the ultrasonic sensor to the 5V pin on the Arduino board.
   - Connect the GND pin to the GND pin on the Arduino board.
   - Connect the TRIG pin to pin 11 on the Arduino board.
   - Connect the ECHO pin to pin 12 on the Arduino board.

2. **Connect LEDs:**
   - Connect the anode (positive) pin of the red LED to pin 4 of the Arduino board through a 220-ohm resistor.
   - Connect the anode (positive) pins of the green LEDs to pins 5, 6, and 7 of the Arduino board, each through a 220-ohm resistor.

3. **Connect LCD Display:**
   - Follow the datasheet for your specific LCD to connect it to the Arduino. Typically, connections include VCC, GND, SDA, and SCL.

4. **Upload Code:**
   - Use the Arduino IDE to write and upload the provided code to the Arduino board.

5. **System Test:**
   - Place an object in front of the sensors and observe the LED indication.
   - The red LED should light up if the object is within 10cm of the IR sensor.
   - The LCD should display the measured distance.

### Installing Arduino IDE
- **For Windows Users:**
  - [Download and Install Arduino IDE](https://www.arduino.cc/en/software)

- **For Linux Users:**
  - Open a terminal.
  - Run the following command to install Arduino IDE:
    ```bash
    yay -S arduino
