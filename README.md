# E-Bike Anti-Theft Immobilizer & GPS Logger

## Overview
Anti-theft system for e-bikes that allows arming/disarming and immobilizes the motor when movement is detected while armed. GPS coordinates are logged to Serial (can be saved to SD or sent via GSM). Includes buzzer alert and motor-disable output.

## Features
- Arm/disarm switch for theft protection
- Cuts motor enable line (relay/MOSFET) when triggered
- Logs GPS coordinates for recovery
- Buzzer alarm for audible alert
- Expandable: add SIM/GSM to send SMS alerts or SD to save logs

## Hardware Required
- Arduino Uno (or similar)
- NEO-6M or similar GPS module
- Relay or MOSFET to cut motor enable line
- Arm/disarm switch
- Buzzer
- (Optional) SIM800L for SMS, SD card module for logging

## Notes & Safety
- Ensure immobilizer wiring does not cut power unsafely; use proper relays / contactors rated for motor currents.
- GPS needs clear sky view for a reliable fix.
- Test with motor disconnected from vehicle before live tests.

---

👨‍💻 **Author:** K. Viswanadh
