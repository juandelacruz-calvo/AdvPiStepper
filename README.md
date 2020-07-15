# AdvPiStepper
AdvPiStepper is a driver for all kinds of stepper motors, written in Python for the Raspberry Pi.

## Features
* Uses acceleration and deceleration ramps
* Fairly tight timing up to {TBD} steps per second.
* Complete API for relative and absolute moves, rotations and continuous running.
* Runs in the background. Motor movements can be blocking or non-blocking.
* Support for microstepping (depending on the driver)
* Support for unipolar stepper motors
    * Like the cheap 28BYJ48 motor
* {TODO} Support for Bipolar stepper drivers / dual H-Bridges like the
    * L293(D)
    * DRV8833 
* {TODO} Support for Step/Direction controllers like
    * A4988 
    * DRV8825
    * STSPIN220 / 820
* Other drivers should be easy to implement
* Licensed under the very permissive MIT license.

## Requirements
AdvPiStepper uses the [pigpio](http://abyz.me.uk/rpi/pigpio/) library to access the Raspberry Pi GPIO pins.
It requires V76 of the library, which at the time of writing has not yet been uploaded to the PyPI archive and
therefore has to be [installed manually](http://abyz.me.uk/rpi/pigpio/download.html).

## Usage
To use the AdvPiStepper {TODO}
