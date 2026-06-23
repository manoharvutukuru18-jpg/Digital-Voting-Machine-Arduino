# Digital Voting Machine with Secure Memory

## Project Overview
A digital voting machine designed using Arduino UNO with LCD display and EEPROM based secure storage.

# Requirements Implementation

## 1. State Machine for Vote Counting Logic

Implemented voting states:

- IDLE State
- Candidate A Vote State
- Candidate B Vote State
- Candidate C Vote State
- Result Display State


## 2. Secure Data Storage using EEPROM

Arduino internal EEPROM is used for storing votes.

Functions used:

EEPROM.write()
EEPROM.read()


## 3. LCD Result Display

16x2 LCD displays:

- Vote confirmation
- Candidate vote count
- Final results


## 4. Debouncing Logic for Tactile Switches

Button debouncing implemented using millis() function to avoid multiple counts.


# Tools Used

- Tinkercad Circuits
- Arduino IDE


# Components

- Arduino UNO
- 16x2 LCD
- Push Buttons
- Breadboard


# Author

VUTUKURU SAI TULASI MANOHAR