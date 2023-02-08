## Members
Devin Cress, Electrical Engineering Student (2025)
dcress94@vt.edu

Alex Betx, Electrical Engineering Student (2025)
abetz01@vt.edu

## Repo Link

## Photo
{% include youtube.html video="miltuOLWDFQ" %}

## Mentor
Richard Gibbons

## Current Status
Hardware development

## Project Overview

The Modular Flight Control and Recovery System, or MFCRS, is an ARM-based flight computer for use in high-powered amateur rockets. The computer will continously monitor and log linear acceleration, rotation, altitude, and compass heading, as well as deploy recovery devices and ignite additional stage motors.

As this is a long-term project and we would like to add additional features in the future (namely telemetry), a modular design has been chosen in which multiple boards are stacked and interconnected via header pins. Four header pins will supply 3.3V, ground, and two I2C lines to every board in the stack, allowing new hardware additions without completely redesigning everything.

The MFCRS will eventually be used in the high powered rocket that we are developing alongside this project - the Lima II.

## Educational Value Added

MFCRS is being developed from the ground up and includes IC selection, PCB design, PCB assembly, and firmware design.

## Tasks

- Design sensor board.
- Design battery board.
- Order sensor and battery boards.
- Test boards with STM32 development board.

- Design and order main processor board.
- Develop STM32 firmware.

## Design Decisions

- STM32M4 was chosen for its low-cost, performance, and availability.
- LSM6DSO32XTR was chosen for its acceleration range (+/-32g)

## Design Misc



## Steps for Documenting Your Design Process

<!-- Your Text Here. See Example above -->

## BOM + Component Cost
Sensor Board
- 1 Accelerometer/gyrometer IC - LSM6DSO32XTR
- 1 Magnetometer IC - IIS2MDCTR
- 1 Barometer IC - BMP390
- 1 4-pin passthrough header
- 6 100nF 0603 ceramic capacitors
- 1 220nF 0603 ceramic capacitor
- 1 10uF 0805 ceramic capacitor

Battery Board
- 1 100mAh LiPo battery - ASR00012
- 1 3v3 low-dropout voltage regulator - LD29080DT33R
- 1 I2C battery gauge IC - MAX17048
- 1 LiPo battery charge IC - MCP73832T
- 1 MicroUSB port - 10118194
- 1 0603 red LED
- Various resistors and capacitors (TBD)


## Timeline

February 2023
- Design and order sensor and battery boards.

March 2023
- Test boards via dev board.
- Begin developing STM32 firmware.

April 2023
- Design and order main processor board.
- Continue firmware development.

## Useful Links



## Log

