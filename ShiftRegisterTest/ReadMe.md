# Simple test for shift register

SN74HC595 is a shift register has this layout:

<!-- add image -->
<div align="center">

![](https://docs.arduino.cc/static/069d6e15e1d905552f71f0826dea38f4/6a91e/595_pin_diagram.png)

</div>

## Connections from arduino
- GND (pin 8) to ground
- Vcc (pin 16) to 5V
- OE (pin 13) to ground
- MR (pin 10) to 5V
- DS (pin 14) to Ardunio DigitalPin 11 (blue wire)
- SH_CP (pin 11) to to Ardunio DigitalPin 12
- ST_CP (pin 12) to Ardunio DigitalPin 8

Add positive lead of leds to pins Q1 to Q7 negative to common ground.

Compile and run this script, you'll see the leds light up.

