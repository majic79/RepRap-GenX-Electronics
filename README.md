# RepRap GenX Electronics

## About
This project contains the hardware schematics and design choices for a low cost printer control board for RepRap hardware. Current boards are very capable, but make decisions on cost and feature set that are not of my choice. By making this available, I aim to add another option out there.

Making the printer control a drop in selection, this will permit re-use of existing driver breakouts (e.g. Pololu A4988's and DRV8825's) and with SPI support for TMC2300 breakouts, it allows an upgrade path. and low cost upgrade potential for existing printer controllers.

__!! Warning - this is still work in progress !!__

This board is based around the ARM MCU STM32F412RGT running at 96MHz in a LQFP-64 package. There are a few free pins, and with some ingenuity, some pins can be multiplexed/multi use.

## Plans

Currently, two DC-DC converters are used, with a 5V middle tier which could be brought out for Pi-Power. Adding a Pi compatible interface and EEPROM would make this recognisable as a HAT and allow communication without a USB interface cable.

Future intent is to port MarlinFW to this package, from the PlatformIO platform. Programmers for these devices are relatively cheap, but there remains the possibility of a 0 cost programming option via the USB DFU device capabilties.

Selling these individually is not possible in todays marketplace without some additional testing and regulation, but those requirements need to be investigated and addressed as development progresses.

As the majority of components are surface mount (SMD) with only a few through-hole components, the plan is to complete the bill of materials (BOM) for the SMD components and send for professional fabrication on the prototypes.

## Milestones

  * ~~Initial Circuit~~
  * ~~MCU Selection~~
  * ~~Power Supplies~~
  * ~~PCB Layout~~
  * RaspberryPi interface
    * EEPROM
    * U(S)ART
    * Back Power
    * Mechanical interface
  * Review
  * Feedback
  * Component Selection (BOM)
  * Fabrication
  * Testing
  * Firmware Development

## News

2020-01-19 - Initial Commit