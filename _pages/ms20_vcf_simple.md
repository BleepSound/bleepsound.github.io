---
permalink: /ms20_vcf_simple/
layout: single
title: "MS20 VCF simple"
category: "Filters"
toc: true
toc_label: "ToC"
toc_icon: "cog"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/MS20-VCF-S-top.png
---

![MS20-VCF-S-top](/assets/images/MS20-VCF-S-top.png)

MS20-VCF clone based on [BartonSynth](https://www.bartonmusicalcircuits.com/synthstuff.html#analog) version.

Size: 10HP

Cutoff + resonance, with a switch to chose low pass or high pass mode.

CV control on the filter cutoff.

Self oscilation if resonance pushed to maximum, can be adjusted with 2 trimmers :

- 1 trimmer for the sine wave amplitude (resVol)
- 1 trimmer for the level at which the knob for resonance starts the self oscillation (resLvl)

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

![single MS20-VCF schematic](/assets/images/MS20-VCF-S--Schematic.svg)

## BoM

[See bom](/assets/bom/MS20-VCF-S_V1.2--iBoM.html)

You can donwload the bom in excel format [here](https://github.com/BleepSound/ms20-vcf-simple/releases/download/v1.2/MS20-VCF_V1.2--BoM.xlsx).

## Build Informations

Uses an SMD LM13700 because the DIP ones are not produced anymore, hence more expensive.

Regular build, I use ceramic capacitors but you can use film/polyester.

:warning: When building modules, always do it in this order (from smallest component to highest):
- diodes
- resistors
- DIP chips
- capacitors (film/ceramic)
- Transistors
- Electrolytic capacitors

For the next part, always place them without soldering them on:
- jacks, pots and switches that go thought the front panel

Once placed, put in place the front panel, then fasten all components to it. Once this is done, you can solder them.

## Images

![3D single MS20-VCF(front)](/assets/images/MS20-VCF-S-3D_top.png)

![3D single MS20-VCF(back)](/assets/images/MS20-VCF-S-3D_bottom.png)

![3D single MS20-VCF(iso)](/assets/images/MS20-VCF-S-3D_top30deg.png)

## Download

Follow this link if you want to dowload the latest version of gerber files, schematic, kicad files...

:arrow_down: [**Download**](https://github.com/BleepSound/ms20-vcf-simple/releases)
