# Flukebox
A portable, off-grid, open-source MP3 player! Supports Bluetooth Classic and analog headphones. 

# PCB Desing

The Flukebox V1.0 uses a two-layer PCB to house all its MCU's, modules, resistors and capacitors. Due to my inexperience in soldering, I didn't feel ready to order a bunch of bare components off Digikey or LCSC and solder them all together. Instead, I ordered modules for the things I needed the Flukebox to do, and am planning to solder them right onto the PCB using cut pin headers or solid wire. I will probably ditch this strategy in a future version, but it'll do for now. At least it makes the schematic and PCB design easier.

![An image of the Flukebox's PCB's schematic](Images/FB15.png)
![An image of  the Flukebox's PCB's design](Images/PB14.png)

# CAD

The CAD for the Flukebox was pretty simple. I gave the PCB a 0.2 mm clearance on both sides, made a case, cut some holes for the USB-C charger and the analog headphone jack, made a lid, cut holes for the OLED, buttons, power switch, and EC11, and that was pretty much it. I have a lot of experience in these things. What was more fun was making an assembly of the finished PCB using KiCad's STEP model and models of the components I'm using I found online. I think it looks super cool! It's just a shame how the pads for the ESP-WROOM-32 didn't render, forcing me to take measurements from KiCad. Oh, well.

![An image of the Flukebox V1.0 PCB assembly](Images/FB16.png)
![An image of the full Flukebox V1.0 assembly](Images/FB13.png)
