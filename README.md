# E-41 LIDAR

**Project Status:** Prototype

If you are new to GitHub and would like to create a derivative of this project, please have a look at GitHub instructions to [fork a repo](https://help.github.com/en/articles/fork-a-repo)

## Description

Out of our passion to solve the issue of time waste in the robot creation process, EZ-Builder was born. The EZ-Builder software platform reduces the time it takes to get from idea to implementation. Since 2011 we have been listening to the challenges robot builders encounter and continue to provide them with an ever expanding toolbox of solutions. Join us on this journey!

We didn't stop at the software, we also made time saving hardware solutions. This LIDAR reference design is one of them. This reference design simplifies the communication from the LIDAR and allows it easily interface to EZ-Builder. EZ-Builder then gives a visual representation of the data and starts mapping the area. We want to share these files with you so you can create your own version for your community and customers to enjoy!

**Features:**
- I2C breakout
- EZ-B Camera breakout
- LIDAR communication breakout
- SWD programming header
- 5V tolerant I/O pins
- Mounting points for LIDAR unit
- 5V energy effecient switching power supply
- EZ-Builder behavior control available
- Reverse polarity protection
- Bicolor Blue/red indicator LED
- Voltage requirement: 5-16VDC (7.4V Typical)
- Dimensions: 149.4(W) x 95.3(L) x 39.6(H) (mm)
- Weight: 166g

**Major components:** 
- STM32F401RBT6 ARM microcontroller (custom firmware provided)
- RT8299GSP Switching power supply 
- HLS-LFCD2 LIDAR unit

**Manufacturing notes:** 
1. Supplier: programs custom firmware into the STM32F401RBT6 at their facility before sending to manufacturer
2. Supplier: provides LIDAR unit
3. Manufacturer: Single side placement and soldering of SMT components
4. Manufacturer: Single Side soldering of THT components
5. Manufacturer: Assembles PCB and LIDAR unit together

## Contents

[**Documentation:**](https://github.com/synthiam/E-41_LIDAR/tree/master/E-41%20Documentation) Schematic PDF, Datasheet PDF, BOM

[**Hardware:**](https://github.com/synthiam/E-41_LIDAR/tree/master/E-41%20Hardware) Altium PCB design File, Altium SCH Design File

[**Firmware:**](https://github.com/synthiam/E-41_LIDAR/tree/master/E-41%20Firmware) Code, Compiled binary

*Altium Libraries are also available <a href="https://github.com/synthiam/Synthiam_Altium_Librairies">here</a>*

## Photos

<p align="left">
<img src="https://live.staticflickr.com/65535/40778036183_b00cbc3a88_k.jpg" width="683" height="383">
<img src="https://live.staticflickr.com/65535/32801179637_d0344c3f3b_k.jpg" width="683" height="383"></p>

## EZ-Builder Behavior Control

The EZ-Builder behavior control for this reference design is very easy to use! Simply add an animation frame, click on the pixels, choose the color, and repeat! Activate the animations with the click of a mouse button or with code. 

Link: https://synthiam.com/Software/Manual/EZ-LIDAR-SLAM-15944

<a href="https://synthiam.com/Software/Manual/EZ-LIDAR-SLAM-15944"><img src="https://media.giphy.com/media/kBMzMoIjNVdNcOrw6s/giphy.gif" width="683" height="383"></a>

## Contact

For profit use of these files requires written consent. Contact partners@synthiam.com. For everyone else, party on!

Synthiam Website: https://synthiam.com

## License

This project is released under the following licenses:

**Hardware:** Creative Commons Plus Attribution-NonCommercial 4.0 International (CC+ BY-NC 4.0)

**Firmware:** Apache 2.0 + “Commons Clause” License Condition v1.0

Please see [LICENSE.md](https://github.com/synthiam/E-41_LIDAR/blob/master/LICENSE.md) for license details.

<a href="https://synthiam.com"><img src="https://live.staticflickr.com/65535/47791527651_358dffb302_m.jpg"></a>
