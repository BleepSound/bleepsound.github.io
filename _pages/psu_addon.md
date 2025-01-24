---
permalink: /psu_addon/
layout: single
title: "PSU Addon"
category: "PSU"
toc: true
toc_label: "ToC"
toc_icon: "cog"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/PSU-addon-top.png
---

![PSU Addon](/assets/images/PSU-addon-top.png)

:warning: **WIP WIP WIP WIP WIP** :warning: 

PSU Addon to create a stable +/-12V voltage for your case. 
Input can be up to 35V **DC**.

This is designed to be used (in my case) with a Meanwell RT65C. Input in my case will be +/-15V. But it can be used with any DC power supply, as long as you have +/-2V above +/-12V on the input.

This PSU-addon will provide a maximum of 1A on each rails ** But check the specs of the PSU you have on the input to make sure that it'll be sufficient. 

The input capacitor is oversized because I had those lying around. But you could use anything a bit smaller. Check the voltage regulators datasheet if you want to make sure. 

## Schematics

![PSU Addon schematic](/assets/images/PSU-addon--Schematic.svg)

## BoM

[See bom](/assets/bom/PSU-addon_V1.1--iBoM.html)

You can donwload the bom in excel format [here](https://github.com/BleepSound/PSU-addon/releases/download/v1.1/PSU-addon_V1.1--BoM.xlsx)


## Build Informations

Put heatsink elements on the voltage regulators, as they will get really hot during use. 

:warning: When building modules, always do it in this order (from smallest component to highest):
- diodes
- resistors
- Electrolytic capacitors (small ones)
- Terminal blocks connectors
- Voltage regulators
- Oversized electrolytic capacitors

## Images

![3D PSU Addon(front)](/assets/images/PSU-addon-3D_top.png)

![3D PSU Addon(back)](/assets/images/PSU-addon-3D_bottom.png)

![3D PSU Addon(iso)](/assets/images/PSU-addon-3D_top30deg.png)

## Download

Follow this link if you want to dowload the latest version of gerber files, schematic, kicad files...

:arrow_down: [**Download**](https://github.com/BleepSound/PSU-addon/releases)

<script src="https://utteranc.es/client.js"
        repo="BleepSound/bleepsound.github.io"
        issue-term="title"
        label="Comment"
        theme="photon-dark"
        crossorigin="anonymous"
        async>
</script>