# Arduino-Mood-Clue

## Overview

This simple project uses a potentiometer and servo motor to create a mechanical gauge that can visually represent different moods or positions.


## Objective

* To control a servo motor using an analog input
* Read potentiometer values using the Arduino's ADC
* Map analog input values to servo motor angles
* Display potentiometer values and servo angles through the Serial Monitor


## Components used

* Arduino board
* Potentiometer
* Servo motor
* 100 µF capacitor
* Breadboard
* Connecting wires


## How It Works

1. Reads the potentiometer value using `analogRead()`.
2. Uses the Arduino's ADC to convert the potentiometer's voltage into a numerical value.
3. Maps the potentiometer value from 0–4095 to a servo angle from 0–179°.
4. Moves the servo to the corresponding angle.
5. Displays the potentiometer value and servo angle through the Serial Monitor.


## What I Learned

* Controlling a servo motor using the Arduino
* Using the built-in Servo library
* Reading analog inputs using the ADC
* Using `map()` to scale values between different ranges
* Using the Serial Monitor to monitor sensor and servo values


## Demonstration

A video showing the potentiometer controlling the servo motor can be seen below.

[Watch the project demonstration](./Arduino_Mood_Cue_demo.mp4)
