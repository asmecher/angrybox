# angrybox
An angry box.

Wiring instructions:
- Connect a small speaker between Arduino digital pin 11 and GND.
- Connect a button between Arduino digital pin 2 and GND.

To move this from the Arduino board to a stand-alone ATMEGA328 chip, you'll
need to set the ATMEGA fuses to tell it to use the internal clock. Follow the
instructions at <https://www.arduino.cc/en/Tutorial/ArduinoToBreadboard>.

In this configuration, you'll be able to build this project with nothing more
than the switch, speaker, ATMEGA chip, and battery.

More information here: http://cassettepunk.com/blog/2015/10/15/angry-box/
