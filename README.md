# Hardware_CSAT

Hardware design files 1 cubesat:
- [EPS board](https://github.com/MatthiasGeorgImhof/Hardware_CSAT/tree/master/eps_board)
  - batteries and battery management for solar cells charging
  - voltage regulatars
  - RTC clock
- [Avionics board](https://github.com/MatthiasGeorgImhof/Hardware_CSAT/tree/master/avionics_board)
  - IMU and magnetometer
  - sun detectors
  - magnetorquer control
- [Science board](https://github.com/MatthiasGeorgImhof/Hardware_CSAT/tree/master/sci_board_wo_switches)
  - cameras and imagers
- [Communication board](https://github.com/MatthiasGeorgImhof/Hardware_CSAT/tree/master/openlst-hw)
  - 435 MHz link
  - ethernet port for satelite modem

In addition, there is also
- [Auxilliary board](https://github.com/MatthiasGeorgImhof/Hardware_CSAT/tree/master/aux_board) that stands provides desktop power and connectivity
  - USB connection to computer
  - voltage regulators

Schematics & Layouts are done using KiCad V9.0

The corresponding software repos are [AUXL496_CSAT for the auxilliary board](https://github.com/MatthiasGeorgImhof/AUXL496_CSAT) and [SCIL496_CSAT for the science board](https://github.com/MatthiasGeorgImhof/SCIL496_CSAT). Software is based on a common architecture [Common_CSAT](https://github.com/MatthiasGeorgImhof/Common_CSAT).
