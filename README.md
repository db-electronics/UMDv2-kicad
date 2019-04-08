# UMDv2
The Universal Mega Dumper v2 project aims to be a complete open-sourced solution for cartridge dumping and writing. It includes a very performant MCU which has a direct memory connection to a generalized databus consisting of 24 address bits and 16 data lines. Along with a dozen or so control signals, it should be sufficient to interface with most cartridge types.

## Cartridge Adapters
The UMDv2 by itself only includes a generalized connector with all its interfacing signals. Cartridge adapters must be used in order to interface to the physical media. These can all be found (as they are designed) in the CartridgeAdapters subfolder.

# Dependencies
## Parts Libraries
All components in this project depend on my KiCad libraries which are available at https://github.com/db-electronics/kicadlib . I don't use any pre-existing libraries - fight me.

## Firmware
There are two firmware components associated with this PCB: the STM32 fimware and the PC-side client. Both are available here:
* https://github.com/db-electronics/UMDv2-stm32
* https://github.com/db-electronics/UMDv2-python

Please note that version 2.0 is in its absolute infancy, don't expect to find any working releases in the firmware links above for the time being. The links are for provided provideness for completeness of documentation.

# Releases
## 2.0
The PCB version 2.0 release files are available in the releases section https://github.com/db-electronics/UMDv2-kicad/releases. Please note that this PCB is as of yet untested. Build at your own risk. I will post updates when I have begun testing this latest release.
