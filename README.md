# DUE3DOM MINI

Modular 3D printer driver working as a shield for 32-bit ARM based Arduino DUE.

![Board](due3dom_mini_asembled.jpg?raw=true "Board")

## Features:
* 20A channel for bed heating (20A fuse) with own power socket
* 10A channel for head heating (10A fuse) with own power socket
* up to 4 external A4988 compatible stepstick drivers (more on expansion port); jumper based step switching
* high current connectors for all power and driver sockets
* input for 4 thermistors (1x onboard; 3x external)
* PWM output for 3 fans
* 4-pin output for board cooling fan driven with signal based on onboard thermistor

## Connections

### Connecting LCD
* EXP1 on DUE3DOM to be connected with EXP2 on SmartController
* EXP2 on DUE3DOM to be connected with EXP1 on SmartController

### Stepstick drivers, motors and other peripherials
![Connections](due3dom_mini_top_wiring.jpg?raw=true "Connections")

## Issues

First board revision (A) needs two manual fixes:
* protection diode [#1](/../../issues/1)
* power on reset capacitor [#2](/../../issues/2)

## Firmware

Supported by official firmware:
* [Repetier](https://www.repetier.com/firmware/dev/index.php)
* [Marlin](https://github.com/esenapaj/Marlin)


## Support
* [Official Website [PL]](http://www.due3dom.pl/)
* [Forum thread [PL/EN]](http://www.fabrykator.pl/board/viewtopic.php?f=12&t=242)

## Where to buy?

* [Seaside Customs](http://fabrykator.pl/seasidecustoms/due3dom-elektronika-32bit-dla-drukarek-3d/)
* Contact: [@dvjcodec](https://github.com/dvjcodec/)

## Demo
[![DUE3DOM MINI + LCD 128x64 - Marlin Firmware](due3dom-mini-yt.jpg?raw=true "Demo")](https://www.youtube.com/watch?v=12baxgj3plI "DUE3DOM MINI + LCD 128x64 - Marlin Firmware")

## License

[CC BY-NC 3.0](https://creativecommons.org/licenses/by-nc/3.0/)

## Authors

Krzysztof @ Seaside Customs
