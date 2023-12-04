***This repo is/will being kept update, the progress depends how busy(lazy) I am*** 😝

# Intro

Build a 3D printer is fun, but it can be also painful while find and organize these of tech staff, mods, configs \
Hence I create this hub and try to consolidate them as a signal entry for 3D printer build guide \
Even this is mainly focus on [Voron](https://vorondesign.com/) and [klipper](https://www.klipper3d.org/) but most of them can be applied for other DIY/Commerical printer as well 

Feel free to raise a ticket at issues tab or submit a commitment if you have anything can be shared \
I can be reached at [![Discord Icon](/images/discord-24.png "Discord") Voron channel](https://discord.gg/voron)  via @jerryji

And happy printing

**Big thanks for all these awsome creators, you guys make all happen!**


## Printer:
[HyperCube](https://www.thingiverse.com/thing:1752766) or [HyperCube Evalution](https://www.thingiverse.com/thing:2254103) \
Salute for these 'legacy' printers, they are the foundation of moderm 3D printer \
Even now, one of my dream is remix it, not only include these advance klipper features but also budget friendly

[Voron](https://vorondesign.com/) \
I don't think we need a comment here... but if you are new for DIY 3D printer, and want build a printer with your own hands, Trident is my recommendation, but after that you will desire a V2 or V0 or SW or Legacy, who knows...

[VzBot](https://github.com/VzBoT3D)
A fast corexy printer series, I mean, very fast

[Annex Engineering](https://github.com/Annex-Engineering)
A fast cross xy gantry printer, AWD driver, make sure your house is strong enough to hold this monster

[HevORT](https://hevort.com/)
A fancy corexy printer with ballscrew at Z axis

[The 100](https://github.com/MSzturc/the100)
THE 100, the fastest 3D Printer based on a printed frame, said by creator which I agree. 
Only concern is you may need a printer to print this printer as its print part can be damaged while printing, no backup printer to print the print part will be painful

## Hardware:

### Overview For A Klipper Printer

#### CAN BUS Staffs
1. Bigtree U2C/EBB32/2209
2. [Katapult](https://github.com/Esoterical/voron_canbus) (formerly known as CanBoot): you can now flash CAN bus based MCU board over CAN bus directly. You **DON'T** need disassemble your MCU board then connect it with your computer via USB connection to upgrade MCU board klipper firmware. 
***Highly recommend***

## SW

Basic Steps:
1. Choose your perferred WebUI with klipper integrated: [Mainsail](https://docs.mainsail.xyz/) / [Fluidd](https://docs.fluidd.xyz/) / [Octoprint](https://octoprint.org/), and burn its image into a SD card
   - Generally they are function the same, but just different UI, choose one you like shall be ok as a start point.
2. Build klipper firmware on the pi for your MCU board and flash it to your MCU board, [Link](https://docs.vorondesign.com/build/software/#firmware-flashing)
3. Config your printer
   1. Config SW
https://docs.vorondesign.com/build/software/configuration.html
   1. Install Tap
https://github.com/VoronDesign/Voron-Tap#post-install-setup
1. Initial check
   1. Motion
   2. Temp

[Klippain - The pain-free recipe for (french)bread and butter Klipper configuration!](https://github.com/Frix-x/klippain)

[Elli's Printer Tuning Guide](https://ellis3dp.com/Print-Tuning-Guide/)

## Mods:
To help you select the right stepper motor:

[Motor Torque Sim](https://github.com/eddietheengineer/documentation/tree/master/stepper_motor/data) 

[An useful belt tension meter](https://github.com/Diyshift/3D-Printer/tree/main/GT2%20Belt%20Tension%20Meter)
<img src="https://github.com/Diyshift/3D-Printer/blob/main/GT2%20Belt%20Tension%20Meter/Images/meteronbelt.JPG?raw=true" width=300>

[DIY Silicone Brush](https://github.com/Diyshift/3D-Printer/tree/main/Silicone%20Brush%20for%20Decontaminator)
<img src="https://github.com/Diyshift/3D-Printer/raw/main/Silicone%20Brush%20for%20Decontaminator/Images/brush_iso.png" width=300>


## Copyrights
This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
