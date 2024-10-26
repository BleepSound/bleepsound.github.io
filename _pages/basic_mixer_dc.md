---
permalink: /basic_mixer_dc/
layout: single
title: "Basic DC mixer"
category: "Mixers"
toc: true
toc_label: "ToC"
toc_icon: "cog"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/Basic-DC-mixer-top.png
---

![Basic-DC-mixer-top](/assets/images/Basic-DC-mixer-top.png)

Basic DC mixer with 4 ins and one out.

DC coupled, can work with both audio and CV.

Mute switches and vol pots on all voices.

One main out and one inverted out.

## Schematics

![basic dc Mixer schematic](/assets/images/Basic-DC-mixer--schematic.svg)

## BoM

[See bom](/assets/bom/Basic-DC-mixer_V1.2--iBoM.html)

You can donwload the bom in excel format [here](https://github.com/BleepSound/basic-mixer-dc/releases/download/v1.2/Basic-DC-mixer_V1.2--BoM.xlsx)

## Build Informations

Regular build, I use ceramic capacitors but you can use film/polyester.

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

![3D Basic-DC-mixer(front)](/assets/images/Basic-DC-mixer-3D_top.png)

![3D Basic-DC-mixer(back)](/assets/images/Basic-DC-mixer-3D_bottom.png)

![3D Basic-DC-mixer(iso)](/assets/images/Basic-DC-mixer-3D_top30deg.png)

## Download

Follow this link if you want to dowload the latest version of gerber files, schematic, kicad files...

:arrow_down: [**Download**](https://github.com/BleepSound/basic-mixer-dc/releases)
