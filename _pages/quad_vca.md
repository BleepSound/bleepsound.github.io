---
permalink: /quad_vca/
layout: single
title: "Quad VCA"
category: "VCA"
toc: true
toc_label: "ToC"
toc_icon: "cog"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/Basic_VCA-top.png
---

![Quad VCA](/assets/images/Basic_VCA-top.png)

:warning: **WIP WIP WIP WIP WIP** :warning: 

Quad VCA module, original design taken from Ray Wilson from [MFOS](https://musicfromouterspace.com/index.php?MAINTAB=SYNTHDIY&VPW=1697&VPH=669)

Possibility to have log and linear response for each VCA via a toggle switch. 

CV inputs are normalled for channel 1-2 and channel 3-4, to have a stereo VCA with one CV signal. 

All outputs are normalled to one another, to use the VCA as an active audio mixer. 

## Schematics

![Quad VCA schematic](/assets/images/Basic_VCA--Schematic.svg)
![Quad VCA schematic](/assets/images/Basic_VCA-VCA_2.svg)

All 4 channels of the VCA are a repeat of this schematic. 

## BoM

[See bom](/assets/bom/Basic_VCA_V1.0--iBoM.html)

You can donwload the bom in excel format [here](https://github.com/BleepSound/basic_vca/releases/download/v1.0/Basic_VCA_V1.0--BoM.xlsx)


## Build Informations

Uses an SMD LM13700 because the DIP ones are not produced anymore (and expensive).

Regular build, I use ceramic capacitors but you can use film/polyester.

Polyester capacitor for the saw core. 

:warning: When building modules, always do it in this order (from smallest component to highest):
- diodes
- resistors
- DIP chips
- capacitors (film/ceramic)
- Transistors
- Electrolytic capacitors

To solder the headers, place them and place both PCBs in their final position before fully soldering the pin headers/sockets.

For the next parts, always place them without soldering them on: 
- jacks, pots and switches that go throught the front panel

Once placed, put the front panel in place, then fasten all components to it. Once this is done, you can solder all the remaining components.

## Images

![3D Quad VCA(front)](/assets/images/Basic_VCA-3D_top.png)

![3D Quad VCA(back)](/assets/images/Basic_VCA-3D_bottom.png)

![3D Quad VCA(iso)](/assets/images/Basic_VCA-3D_top30deg.png)

## Download

Follow this link if you want to dowload the latest version of gerber files, schematic, kicad files...

:arrow_down: [**Download**](https://github.com/BleepSound/basic_vca/releases)