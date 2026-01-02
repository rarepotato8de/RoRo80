# RoRo80: A custom 80% PCB for "Pete" 📉

The **RoRo80** is a custom-designed TKL PCB created for the keyboard enthusiast group **"Pete"**. Named as a tribute to the legendary German debt counselor Peter Zwegat (a community inside joke). There have been multiple versions from the RoRo80, which all have been produced and tested!
Here are the most recent solder and hotswap versions.

Hotswap:
<img width="2548" height="958" alt="RoRo80_Banner" src="https://github.com/user-attachments/assets/9849fcd0-dbd3-49bd-adc0-5a59948275f1"/>

Solder:
<img width="2360" height="901" alt="image" src="https://github.com/user-attachments/assets/3b8369f5-b581-4f98-a4b1-a567e9f94fea" />

## Two Flavors: Hotswap & Solder
The RoRo80 comes in two different versions to suit your build preference:

| Feature | Hotswap Version | Solder Version |
| :--- | :--- | :--- |
| **Switches** | Kailh Hotswap Sockets | Solder |
| **Indicators** | Caps- & Scroll-Lock LEDs | None |
| **Underglow** | None | **RGB Underglow** (Bottom Side) |
| **Bottom Row** | 7U Tsangan Only | 7U Tsangan AND Standard Bottom Row |

## Features
* **Compatibility:** H87/H88 Form Factor
* **Chipset:** RP2040
* **Mounting:** O-Ring cutouts & versatile mounting support
* **Connectivity:** Breakable USB-C port (JST-header for Daughterboards)
* **Software:** Full QMK & VIAL Support

## Firmware & Flashing
The RoRo80 uses the UF2 bootloader, making flashing as easy as using a USB thumb drive.

1. **First time:** Plug the PCB in. A drive named `RPI-RP2` will appear.
2. **Flash:** Drag and drop the `firmware.uf2` file into that drive.
3. **Subsequent times:** Hold the **BOOT** button, press **RESET** twice, then release **BOOT**.

> [!TIP]
> You can find the latest VIAL firmware in the `/firmware` folder of this repository.

## Supported Layouts
* **Common:** 7U Tsangan Bottom Row, Stepped CapsLock, Split Backspace & Split Right Shift, F12/F13
* **ISO/ANSI:** Both versions support ISO and ANSI
* **Caps:** Solder has both normal and stepped, Hotswap ONLY has stepped

## Breakable USB-C Port
> [!CAUTION]
> **Safety Warning:** Removing the USB-C port creates FR4 (fiberglass) dust. 
> * Wear a **mask** and **eye protection**.
> * Use pliers to carefully wiggle the port until it snaps off cleanly.

## Inside the RoRo80 HOTSWAP
Here's a look at the PCB design from KiCad. It's where all the magic happens!
<img width="1981" height="819" alt="KiCad_PCB_Design" src="https://github.com/user-attachments/assets/839c19f9-172f-47bd-991a-b10e93aa042a"/>

## The Story behind "Pete"
The project started in 2022 within the "Pete" enthusiast group. The name is a humorous nod to Peter Zwegat—because let's be honest: in this hobby, we are all just one group-buy away from needing professional financial advice. 

The RoRo80 was developed to provide the group with a reliable, easy-to-configure RP2040 PCB that fits a variety of popular TKL cases, combining community memes with serious engineering.
Two friends of the Pete Group, **Roman and Rohaly**, asked me to design a PCB for all of us. That's what I did and named the PCB after these two guys: **Ro-Ro**.

---

## Open Source
This project is part of the open-source keyboard movement. Files will be released to the public soon!

## Questions?
Feel free to open an issue or message me directly!

**Shoutout to the Pete-Group!** 📉❤️
