# Smart Water Level Monitoring System

## Overview

The **Smart Water Level Monitoring System** is an IoT-based project that helps monitor the water level in a tank and prevents overflow. It uses an ultrasonic sensor to measure the water level and alerts the user using a buzzer when the water reaches a specified limit.

## Objective

* To monitor water level in a tank
* To prevent water overflow and wastage
* To provide alert notification when tank is nearly full

## Components Used

* Arduino
* Ultrasonic Sensor (HC-SR04)
* LCD Display
* Buzzer
* Jumper Wires

## Features

* Measures water level using ultrasonic sensor
* Displays water level on LCD screen
* Buzzer alert when water reaches 80%
* Prevents water overflow

## Workflow

1. Initially, the water level is 0% (empty tank).
2. The ultrasonic sensor continuously measures the distance between the sensor and water surface.
3. As water is added, the level increases and is calculated by the Arduino.
4. The current water level is displayed on the LCD display.
5. When the water level reaches the specified limit (80%),
6. The buzzer is activated
7. The user gets alerted
8. The user can then turn OFF the motor manually, preventing overflow and water leakage.

## Setup Instructions

1. Connect ultrasonic sensor to Arduino:
   * VCC → 5V
   * GND → GND
   * TRIG → Digital Pin
   * ECHO → Digital Pin
2. Connect LCD display to Arduino
3. Connect buzzer to a digital pin
4. Upload the code using Arduino IDE
5. Power the system and place sensor at the top of the tank

## Output

* LCD displays current water level
* Buzzer sounds at 80% level

## Future Enhancements

* Automatic motor ON/OFF system
* Mobile app notification
* IoT-based remote monitoring
