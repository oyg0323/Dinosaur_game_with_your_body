# Dino Game Real Jump

## Overview
This is an Arduino-based implementation of the Chrome browser's Dinosaur Game, where real jump movements are detected to make the dinosaur jump.

## Features
- **Real Jump Detection**: Uses an accelerometer sensor to detect the user's jumping motion
- **Arduino Compatible**: Works with various Arduino boards
- **Simple Controls**: Play using only jump movements

## Requirements
- Arduino board (e.g., Arduino Uno)
- Accelerometer sensor (e.g., MPU6050)
- OLED display (optional)
- Jumper wires and breadboard

## Installation and Setup
1. Install Arduino IDE.
2. Open the `dino_game_real_jump.ino` file in Arduino IDE.
3. Install necessary libraries (MPU6050, Adafruit GFX, etc.).
4. Connect the Arduino board to the PC and upload the code.
5. Connect the sensor to the board and test the jump detection.

## How to Play
- The user jumps, and the sensor detects the movement, making the dinosaur jump.
- Obstacles appear at intervals, requiring precise jump timing.
- The goal is to survive as long as possible.
- The game runs in the Chrome browser.

## Contribution
1. Fork this repository.
2. Add new features or fix bugs.
3. Commit your changes and create a pull request (PR).

## License
This project is licensed under the MIT License.

