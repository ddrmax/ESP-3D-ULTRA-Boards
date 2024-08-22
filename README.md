# ESP-3D-ULTRA-Boards
A new customisable Design based on the ESP32 MCU for 3D Printing and CNC / Laser Cutting boards and drop-in replacement for common 3d printers boards. Design specific to support Marlin 2.1.X firmware and a maximum of the features.

## Design Goals and supported features
Extensible design to support for up to 10 independent coordinated linear/rotary axes for custom applications
Extensible design to support for up to 8 extruder heaters or 9 heated beds (for example a 3x3 heated bed setup for big DIY CORE XY Style 3D printers) 
Extensible design to support for up to 8 PWM FANs and 8 Switched FANs
## License

Schematics and Designs are all licenced under the **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)** license by default.
Each drop in replacement boards will have a readme with links to buy the mounted PCB on major PCB manufacturers and assemblers like PCBWAY and OSHLAB (JLCPCB). 

## Boards sold on Etsy and Ebay and other platforms
As of today no one is allowed to sell my designs. 
In the future it may be possible (Generic designs and new layouts only) and Drop-in replacements will never be allowed to be sold. 
If you end up on one of my designs for sale, please open an issue and report the seller to the platform indicating their are selling counterfeit hardware.
If a seller is allowed, it will be linked either here on on  a dedicated Authorised Sellers.md that would be linked here. 

# Boards Design and Generic PCBs

Major Designs will be created with Generic PCBs but none of them will be "working as is" because making prototype of each boards is costly.
Only those that are marked "tested" or "community tested" could be trusted as working, each of them will have configuration files, and if an integrated feature doesn't exists in Marlin Firmware, a link to the dedicated fork adding those features will be available. 
My Goal is to make those new features upstream into the original Marlin codebase.

## Drop in Replacement

Some Drop-in replacements will be made available with the same care as of the generic boards designs, with config files and compilation helpers and a .bin file to flash directly.
Here are some examples of drop-in replacements that i will design myself:

 - Anet V1.0 board (on most Anet A8)
 - Melzi 2.0 board (on most older Tronxy 3D printers)
 - Ender 3 mainboard (the 8 bit version)

these designs will replicate the size, mounting holes, connector pinouts and placement of the original motherboard, and they will be working like the original without any hardware modifications 

# Community Help
All the help from the community is highly regarded and contributions will credited in the readme or in contributors.md
## Contributors
### Tier 1 Contributors: Hardware and Software design
 [ddrmax](https://github.com/ddrmax)
### Tier 2 Contributors: Hardware design only
No contributors
### Tier 3 Contributors: Software design only
No contributors
### Testers Tier Contributors: Testing designs
 [ddrmax](https://github.com/ddrmax)
### Debuggers Tier Contributors: Debugging designs
 [ddrmax](https://github.com/ddrmax)
### Special Thanks: Ideas Proposals and other
