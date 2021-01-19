# RepRap GenX Electronics

## About
This project contains the hardware schematics and design choices for a low cost printer control board for RepRap hardware. Current boards are very capable, but make decisions on cost and feature set that are not of my choice. By making this available, I aim to add another option out there.

__!! Warning - this is still work in progress !!__

This board is based around the ARM MCU STM32F412RGT running at 96MHz in a LQFP-64 package. There are a few free pins, and with some ingenuity, some pins can be multiplexed/multi use.

## Plans

Future intent is to port MarlinFW to this package, from the PlatformIO platform. Programmers for these devices are relatively cheap, but there remains the possibility of a 0 cost programming option via the USB DFU device capabilties.

Selling these individually is not possible in todays marketplace without some additional testing and regulation, but those requirements need to be investigated and addressed as development progresses.

## News

2020-01-19 - Initial Commit