# ALog-BottleLogger2.2
Arduino-based low-power field environmental data logging platform: hardware schematics and circuit board layouts
Changes from V2:
1) Added second EEPROM U13 in parallel with U19 to increase local storage from 2Mb to 4Mb (0.5MB)
2) Added pullup resistor R58 to TP1 32kHz output
3) Changed U22 and U4 schematic symbols
4) Added R59 Pullup resistor to eliminate any possibility of glitching whenever U23 switches from RS485/SDI-12 
   receive mode over to RTC alarm mode wakeup trigger input. Probably not required(but makes me feel better:-) )
