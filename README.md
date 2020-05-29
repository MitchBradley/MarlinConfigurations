# MarlinConfigurations
Marlin configuration files for some 3D printers I own or manage

Each printer has its own branch

## JGAuroraA5 is a JG Aurora A5 with these mods:
* Direct extruder
* No filament runout sensor
* Modified firmware for the LCD touchscreen
    from  https://jgaurorawiki.com/a5/lcd-firmware
    The mks_config.txt file needs to be edited to change
    the network parameters

## Ender3_BIQU is a Creality Ender with these mods:
* Melzi mainboard replaced by a BIQU Base V1.0,
  because the Melzi's extruder driver chip died.
* Ender display replaced by a ReprapDiscountSmartController
  (2004 text display) - because the Ender display
  has no SD card slot - it is on the Melzi board,
  and the BIQU Base V1.0 has no SD, so we needed
  a display with an SD card slot.
* Belongs to Kevin McDonald

## BigDelta is a large delta printer that Kevin McDonald designed and built.
* Its controller is an https://github.com/MitchBradley/Esp32PrinterController
* The steppers have external drivers with closed loop feedback.
* The print head can be replaced by a spindle

## Anycubic_ESP is an Anycubic i3 with these mods:
* Mainboard replaced by an https://github.com/MitchBradley/Esp32PrinterController
* Ender 3 LCD display
* Bltouch
* Belongs to Karl Hill
