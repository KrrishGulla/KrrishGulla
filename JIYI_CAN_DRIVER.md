# ArduPilot JIYI CAN Rangefinder Driver

A new rangefinder driver for JIYI Microbrain radar sensors (UAV-R21-1, UAV-H30-1), written from scratch for ArduPilot's sensor backend.

## Background

JIYI radar sensors communicate over CAN bus using a proprietary protocol not previously supported in ArduPilot. This driver was written during an internship at Marut Dronetech as part of a GPS-denied indoor drone navigation stack.

## What I reverse-engineered

- CAN frame ID: `0x00D6`
- Magic word: `0xEA2D` (bytes 0-1)
- Distance: bytes 4-5, big-endian uint16, unit in cm

## Files added

- `libraries/AP_RangeFinder/AP_RangeFinder_JIYI_CAN.h`
- `libraries/AP_RangeFinder/AP_RangeFinder_JIYI_CAN.cpp`

## Hardware context

- Flight controller: Cube Orange+
- Sensors: NRA24 (24GHz terrain radar), MR72 (77GHz obstacle radar)
- Used with DroneCAN and direct CAN bus
