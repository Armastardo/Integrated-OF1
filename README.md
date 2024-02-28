# Integrated-OF1
RaspberryPi Pico-powered board compatible with Rev 1 Heavy and Rev 1/2 Light cases (to be sold in waves on the Frame1.gg website).
  
<p align="center">
  <img src="https://github.com/Armastardo/Integrated-OF1/blob/main/Pictures/Render.png?raw=true" />
</p>

Design files are available in this repository. Production files for JLCPCB in the releases page. Currently untested.

## Table of contents
* [Features](#features)
* [Usage](#usage)
* [Acknowledgements](#acknowledgements)

## Features
- USB-C to GCC and USB-C to N64 cable compatible with integrated port.
- Uses [HayBox](https://github.com/JonnyHaystack/HayBox) and [Pico Rectangle](https://github.com/JulienBernard3383279/pico-rectangle) default pinout.

## Usage
1. Order via JLCPCB using the production files in the releases page.
2. Connect them to the PC and the first time it'll show up as a mass storage device.
3. Drop your prefered firmware in uf2 format and once it disconnects it should be good to go.
	- If you connect while pressing the BOOT button (or shorting the pads in the back), it'll show again as a mass storage device so you can update the firmware or replace it.
	- You can also press START on connect if using HayBox or CRIGHT if using pico-rectangle.

## Acknowledgements:
- Greg Turbo: For creating the Frame1 and the Open Frame 1.
- Crane's Lab discord server: For the community that inspired me to create things like this.

### Made using the Open Rectangle Template
OpenRectangleTemplate project - https://github.com/Armastardo/OpenRectangleTemplate
