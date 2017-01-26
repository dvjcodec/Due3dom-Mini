# Due3dom-Mini
Tested, fully working shield for Arduino DUE - DUE3DOM MINI

## Features:

- up to 4 drivers (more on expansion port)
- up to 4 thermistors (one on board)
- up to 3 fans,
- 12-24V power supply,
- separate power supply for bed, hotend and rest electronic
- 12V fans (with 24V power supply in)
- 3 fuses

EAGLE files, BOM (for large version, but 99% electronic components have same), photos.

## IMPORTANT !!! Need to fix 2 places:
 - Add 10uF capacitor between GND and RESET pin
 - Add diode to DUE 12V poewr line (just cut and add 1A diode)

EXP1 on DUE3DOM = EXP2 on SmartController
EXP2 on DUE3DOM = EXP1 on SmartController

## This is rev. A, but tested with a lot of people.

Supported by Repetier and Marlin DUO:
https://www.repetier.com/firmware/dev/index.php
https://github.com/esenapaj/Marlin

This electronic created with hudge support from Fabrykator.pl boards comunity.

### Official website (Polish only at now) --> http://www.due3dom.pl
### Official thread on Fabrykator.pl --> http://www.fabrykator.pl/board/viewtopic.php?f=12&t=242
