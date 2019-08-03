# Description
The goal of this project is to build a hardware game console, develop the firmware to emulate the NES processor on an STM32 processor to enable the console to run NES games.

My partner Jeff and I designed and built this project for UCSB ECE153B class. The idea is from Jeff because he is a big fan of NES games, and he always wanted to work on a project like this. For me, even though I am not interested in NES as much as him, the engineering process this project may involve did attract me.

## This project is challenging in the following aspects:
- We need to finish the hardware design in only one week, including system design, components selection, schematic design, and PCB layout design.
- We must make sure the system doesn't have any hardware-level mistakes in the version.
- 24bits Parallel LCD screen is used in this system, which puts another layer of difficulty in ports planning, PCB layout work, and firmware development work.
- External SDRAM is used, which makes it harder to plan the ports and draw the PCB routes.
- Developing the firmware to emulate NES CPU and PPU is tedious. 

## The whole project can be divided into the following phrases:
- planing the functionalities
- designing the hardware systems
- choosing the components
- designing, manufacturing and assembling the  PCBs
- developing the firmware

# Progress
Currently, we finished the PCB board design and assembly work. The driver-level firmware has been completed and tested. CPU and PPU are almost finished but still need to solve bugs and proceed more tests. (Updated 07/28/2019)
