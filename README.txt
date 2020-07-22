Barber's pole for SMEP ZVT PP 01
================================

Author: Jakub Jermář
Version: 2.0.b
Date: July 22, 2020

This is a short demo program in Intel 8080 assembly that draws an
approximation of the rotating barber's pole on the SMEP ZVT PP 01
microcomputer. The aim is to demonstrate a simple effect achieved
via the hardware-scroll feature of the PP 01.

The program redraws the entire screen in one go, so there is no need to
clear the screen before running it. The program is linked to address
0x1000. You can run the attached barber.ppb to load it.

This is version 2.0.b. The .b is for one-byte memory and video RAM
accesses.

The binary is 114 bytes long, including the code which draws the black
border and the code which scrolls the screen.
