# E-BOT Maze Run

### COE538 F2024
> An autonomous maze navigation system capable of learning and solving a maze using assembly language.

### Table of Contents
- [Project Description](https://github.com/asce2619/E-BOT-Maze-Run#project-description)
- [Tools and Framework](https://github.com/asce2619/SyncEd#Tools-and-Framework)

## Project Description
This project centers around the development of a robot equipped with a sophisticated guidance system. The guider is designed to follow a line on the ground, utilizing a set of photoresistors and LEDs for sensing the environment. While the bot traverses through the maze it identifies dead ends and retraces its path back to the start of a junction when it encounters an obstacle. The robot "learns" the correct path through trial and error.

## Tools and Framework
**Microcontrollers:** HCS12

**Programming Languages:** Assembly using CodeWarrior

**Concepts:**
- Line following algorithms.
- State machine design.
- Analog-to-digital conversion.

## Key Features
- Line Tracking
  - Differential sensors (E-F) for precise line alignment.
  - Pattern detectors (A, B, C, D) to interpret line shapes and junctions.
- Maze Solving Algorithm
  - Detects intersections using sensor data.
  - Left hand focused when making turns. 
- Collision Detection
  - Employs bumper sensors to identify obstacles.
  - Executes 180-degree turns at dead ends and returns to the junction.
 
## Subsystems
**Sensor Scanner:** Reads and thresholds photodetector signals.

**Navigation Manager:** Tracks intersections and makes decisions.

**Motor Controller:** Adjusts motor speeds for steering and turning.

**Data Conversion:** Converts data for the LCD between BCD and ASCII. 

## Challenges
#### Key Lessons:
- The importance of incremental development and testing.
- Challenges of integrating hardware and software in real-time systems.
- Utilizing pseudocode to plan and debug complex logic.
#### Hurdles Overcome:
- Organizing a large set of code containing multiple subroutines.
- Resolving sensor crosstalk and ensuring accurate light detection.

## Authors
Jannis Saini

Neha Rajeev Gogate

Najiba Imam

## Video Demo

