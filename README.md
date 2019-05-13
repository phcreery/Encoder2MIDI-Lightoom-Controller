# Encoder2MIDI-Lightoom-Controller
Use Rotary Encoders to control Lightroom via Arduino and MIDI connection

## Getting Started

This is created to use several rotary encoders as contoller knobs to adjust lightroom sliders

### Hardware

Tested:
 - Arduino Pro Micro

Should Work:
 - Arduino Leonardo
 - Atmega 32U4 based microcontroller

### Prerequisites

Used Libraries
 - https://github.com/adafruit/Adafruit-MCP23017-Arduino-Library/
 - https://github.com/arduino-libraries/MIDIUSB

Lighroom uses the MIDI2LR Plug-in
 - https://rsjaffe.github.io/MIDI2LR/

### Wiring Example

(todo)

## Goals
This is the list of future changes:

 - [X] Send MIDI commands
 - [ ] Clean Up code to smooth adaptivity (ex. allow more than 2 MCP devices and more encoders)
 - [x] Use interrupts instead of constantly checking. This will allow smoother input and is just proper programming
 - [ ] Bottons - Short, Long, Hold and turn.
 - [ ] LEDs
 - [ ] Banks



## Authors

* **Peyton Creery** - *Initial work* - [Website](https://twinsphotography.net)
