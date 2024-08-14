# Time-of-Flight (ToF) PCB 

Contains optical transceiver for lidar or optical communication applications.

Laser diode options:
-  OPV310
-  SPL90 (not extensively tested)
   - Mods required: The A version of the NCP81074A of the MOSFET driver should be used. The supply voltage for the Mosfet driver should be increased from 5V to 12V. The peak power can be considerably increased with a higher voltage and lower shunt resistor value. In this case the duty cycle should be increased correspondingly for eye safety.

  
Photo diodes options:
- MTAPD-06-013
- SiPM MICRORB-10020-MLP-TR1

## Libraries

Uses the following libraries:
- KiCad Symbol Library: [ioda_symbols](https://github.com/plex1/ioda_symbols)
- KiCad Footprint Library: [ioda_footprints](https://github.com/plex1/ioda_footprints)

## Image
![Render](https://github.com/plex1/Tof_PCB/blob/master/outputs/Tof_PCB.jpg)
