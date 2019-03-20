# EstlcamShield
<p align="center">
  <img width="600" src="/images/Front.jpg">
</p>

[![gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg)](https://gitter.im/EstlcamShield/community)
![license](https://img.shields.io/badge/license-CC%20BY--SA%204.0-blue.svg)

## About
The EstlcamShield is a **free** and **open source** PCB design which provides full functionallity of the Estlcam Software. All software-supported pins are provided on the PCB via seperate headers. This shield is specifically designed to work with the [MPCNC](https://www.v1engineering.com/specifications/).

## Component List
- 1x Arduino Mega 2560
- 3x DRV8825 Stepper Driver Board
- 3x 35V 100uF Capacitor (Through Hole)
- 1x KF301-2P Terminal Block (or simmilar)
- 0-9x jumper cap for microstepping
- long female pin headers 2.54mm (I used 8 pin ones)
- regular male pin headers 2.54mm

## Getting Started
You basically have **three** different options:
- Use the included .zip folder, which contains Gerber files, to order your custom PCB from a manufacturer of your choice
- Etch or mill the PCB yourself
- Hit me up on Gitter or via eMail because I ordered a few spare PCBs which I am not using

After you have produced/bought the PCB, solder the necessary components and stack the shield onto your Arduino Mega 2560. Then connect it to your computer and flash the Arduino in the settings of the Estlcam software. You can find good videos about this process on YouTube (the process is simmilar on the Arduino Uno).

Congratulations, you are now running Estlcam in combination with your Arduino Mega! Enjoy 🎉

## License Information

This PCB shield design is based on the [MegaShield_Kit](https://github.com/sparkfun/MegaShield_Kit) from SparkFun, which provided the basic dimensions of the PCB -> Thank you very much!

The hardware is released under [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).

## Limitations
This PCB Design is provided as-is!

Please feel free to adapt it to your needs. I would be very grateful to include your inprovements. Thanks for your support!

**WARNING:** Everyone is responsible for what he/she is doing! I am not responsible if you hurt yourself, torch your house or anything that kind trying to build your own CNC! You are doing everything at your own risk!
