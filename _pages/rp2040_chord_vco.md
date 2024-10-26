---
permalink: /rp2040_chord_vco/
layout: single
title: "RP2040 VCO (Clone, made by Hagiwo)"
category: "VCO"
toc: true
toc_label: "ToC"
toc_icon: "cog"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/RP2040-VCO-top.png
---

![RP2040 VCO top](/assets/images/RP2040-VCO-top.png)

VCO clone, originally made by HAGIWO ([link](https://note.com/solder_state/n/n64b91a171218) in japanese)

RP2040 chord VCO clone in SMD.

5-polyphonic Chord VCO module.
There are 8 types of tones.
With a built-in quantizer and automatic harmonics function, if you input a suitable CV, it will play a nice chord progression.

**Switch indications:**

You'll notice numbers along the central 3 position switch. The table below explains each position's function. 

| Position |      Function      |
|----------|:------------------:|
|     1    |      arpeggio      |
|----------|:------------------:|
|     2    |  chord with root   |
|----------|:------------------:|
|     3    | chord without root |

## Schematics

![RP2040 VCO schematic](/assets/images/RP2040-VCO--Schematic.svg)

## BoM

[See bom](/assets/bom/RP2040-VCO_V1.2--iBoM.html)

You can donwload the bom in excel format [here](https://github.com/BleepSound/rp2040-chord-vco/releases/download/V1.3/RP2040-VCO_V1.2--BoM.xlsx)

## Build Informations

Full CMS build

:warning: When building this module, do it in this order (from smallest component to highest):

- Start by soldering all the CMS components in the order you want on both sides of the PCB.
- Then do all the through hole components
- To solder the headers, place them and place both PCBs in their final postion before fully soldering the pin headers/sockets.

For the next parts, always place them without soldering them on: 
- jacks, pots and switches that go throught the front panel

Once placed, put the front panel in place, then fasten all components to it. Once this is done, you can solder all the remaining components.

## Images

![3D (front)](/assets/images/RP2040-VCO-3D_top.png)

![3D (back)](/assets/images/RP2040-VCO-3D_bottom.png)

![3D (iso)](/assets/images/RP2040-VCO-3D_top30deg.png)

## Software

You can download the software for that module [here](https://github.com/BleepSound/rp2040-chord-vco/releases/download/V1.3/Rp2040.ino) or in the download link below.

The microcontroler model is: **Seeed XIAO RP2040**

To flash it, use a usb-c cable to connect the RP2040 to your computer and use the arduino IDE (or your preferred IDE) to flash the microcontroler.

If you need any help, you can find a tutorial on how to flash a software via arduino onto the RP2040 [here](https://wiki.seeedstudio.com/XIAO-RP2040-with-Arduino/).

## Version

### V1.1
- you HAVE TO rotate SW1 180° for the built in LED to work.
- Issues on front panel (wrong label and missing info)

### V1.2
 - Fix issues on SW1
 - Update front panel look to include all informations

## Download

Follow this link if you want to dowload the latest version of gerber files, schematic, kicad files...

:arrow_down: [**Download**](https://github.com/BleepSound/rp2040-chord-vco/releases)