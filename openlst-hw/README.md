# Communication Board #


This is an iteration on the OpenLST CC1110 based design, which itself is a simplified version of the TI CC1110 432 MHz reference design.
While the CC1110 can operate over 400-470MHz, this board is designed to operate around 435MHz, within the 435MHz-438MHz US Amateur radio band.
See the [FCC's chart, specifically section 5.282](https://transition.fcc.gov/oet/spectrum/table/fcctable.pdf)

- STM32L496 microprocessor
- TI CC1110 co-processor for 435 MHz communication
- Ethernet modem

![communication board](https://github.com/MatthiasGeorgImhof/Hardware_CSAT/blob/master/openlst-hw/openlst-hw.png "communication board")


OpenLST Reference Hardware
==========================

This repository contains a KiCad project with a hardware reference
implementation for the OpenLST.  This design is a simplified version
of the Texas Instruments CC1110 432 MHz reference design.  A 1 watt
power amplifier module has been added to increase operating range.
The design is intended for use at 437 MHz, however, it may be modified
for use at other frequencies.

The user is responsible for obtaining and maintaining the necessary
license to operate this radio.  The example project uses frequencies
in the US Amateur Radio UHF band. Transmissions in this band require a
valid FCC license and compliance with CFR Part 97.

License & Legal Information
---------------------------

Copyright 2018 Planet Labs Inc. This work is licensed under a
Creative Commons Attribution-ShareAlike 4.0 International License.

This document may contain technology or software the export of which
is or may be restricted by the Export Administration Act and the
Export Administration Regulations (EAR), 15 C.F.R. parts
730-774. Diversion contrary to U.S. law is prohibited.
