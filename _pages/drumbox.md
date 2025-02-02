---
permalink: /drumbox/
layout: single
title: "Drumbox"
category: "Percusion"
toc: true
toc_label: "ToC"
toc_icon: "cog"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/Drumbox-top.png
---

![Drumbox](/assets/images/Drumbox-top.png)

:warning: **WIP WIP WIP WIP WIP** :warning: 

The Drumbox is a drum machine soundbox with 6 sounds. The originial idea for this module came from this [website](https://www.sonelec-musique.com/electronique_realisations_gene_percus_001.html) (in french). My first version was not fully operational. 

I modified it to make it work with Eurorack, then I saw that Sam from [LMNC](https://www.lookmumnocomputer.com/projects#/2700-twin-t-drummer) did a similar version, so I did use his work to upgrade my version, which is now basicaly a clone of his :). 

Basic DrumMachine, 6 sounds:
- Kick
- High and Low Bongo
- Clave
- Snare (using the Noise and LowBongo at the same time)
- Noise

Decay control on all those sounds. No CV. 

Individual outputs per sound and one mix output. 

## Module Specs

Eurorack standard, 3U 10HP

|   rail   |      Power         |
|----------|:------------------:|
|   +12V   |        -mA         |
|----------|:------------------:|
|   -12V   |        -mA         |
|----------|:------------------:|
|    5V    |         0mA        |

## Schematics

![Drumbox schematic](/assets/images/Drumbox--Schematic.svg)
![Drumbox schematic](/assets/images/Drumbox-Socket.svg)

## BoM

[See bom](/assets/bom/Drumbox_V1.0--iBoM.html)

You can donwload the bom in excel format [here](https://github.com/BleepSound/drumbox/releases/download/v1.0/Drumbox_V1.0--BoM.xlsx)


## Build Informations

Regular build, I use ceramic capacitors and box capacitors. 

:warning: When building modules, always do it in this order (from smallest component to highest):
- diodes
- resistors
- DIP chips
- capacitors (film/ceramic/box)
- Transistors
- Electrolytic capacitors

To solder the headers, place them and place both PCBs in their final position before fully soldering the pin headers/sockets.

For the next parts, always place them without soldering them on: 
- jacks, pots and switches that go throught the front panel

Once placed, put the front panel in place, then fasten all components to it. Once this is done, you can solder all the remaining components.

## Images

![3D Drumbox(front)](/assets/images/Drumbox-3D_top.png)

![3D Drumbox(back)](/assets/images/Drumbox-3D_bottom.png)

![3D Drumbox(iso)](/assets/images/Drumbox-3D_top30deg.png)

## Download

Follow this link if you want to dowload the latest version of gerber files, schematic, kicad files...

:arrow_down: [**Download**](https://github.com/BleepSound/drumbox/releases)
