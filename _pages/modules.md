---
permalink: /modules/
layout: single
title: "Bleep Sound modules"
toc: true
toc_label: "ToC"
toc_icon: "cog"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/home_page.png
---

Following the links below will take you to the module details. Pay attention to the symbols to see if the project is finished or not. 

**Not all projects are finished or even perfect, use at your own risks.**

## Filters

- MS20-VCF
    - MS-20 clones built around the LM13700 chip
    - :heavy_check_mark: [Simple MS20 VCF](/ms20_vcf_simple/):
        - 1 LM13700 filter with a Low pass or High pass switch with CV for cutoff
        - Based on barton's version : ([link](https://www.bartonmusicalcircuits.com/synthstuff.html#analog))
    - :heavy_check_mark: [Double MS20-VCF](/ms20_vcf_double/)
        - 2 filters in one, each with Low pass or High pass with a possibility to bridge them and get a band pass filter with CV for cutoff
        - Based on barton's version ([link](https://www.bartonmusicalcircuits.com/synthstuff.html#analog))

## Mixers

- :heavy_check_mark: [Basic DC mixer](/basic_mixer_dc/)
    - 4 channel active mixer with mute option with DC coupling (Audio+CV)

## Multiple

- :heavy_check_mark: [3x2 multiple](/multiple/)
    - 3x2 passive multiple (3 inputs to 2 output each)
    - cascade the first input to all outputs if no other input is plugged in

## VCOs

- :heavy_check_mark: [RP2040 chord VCO](/rp2040_chord_vco/)
    - VCO clone, originally made by HAGIWO ([link](https://note.com/solder_state/n/n64b91a171218) in japanese)
    - RP2040 chord VCO clone in SMD.
    - 5-polyphonic Chord VCO module. There are 8 types of tones. With a built-in quantizer and automatic harmonics function, if you input a suitable CV, it will play a nice chord progression. 
- :warning: [CD40106-VCO](/cd40106_vco/)
    - CD40106 saw core oscillator based on Moritz Klein version (https://www.ericasynths.lv/shop/diy-kits-1/edu-diy-vco/)
        - 4 waveforms
            - Saw
            - Square with PWM control
            - Triangle
            - Sine
        - 5 octave switch
        - 1v/oct CV, FM CV and PWM CV.
        - Sync input
        - Extender pins to future Sub octave extender

## ADSRs

- :heavy_check_mark: [Basic ADSR](/basic_adsr/)
    - Basic ADSR based on René Schmitz [Fastest envelope in the West](https://www.schmitzbits.de/adsr.html)
    - All you need in an ADSR
    - Switch to have 2 different time constants for the ADSR

## VCAs

- :warning: [Quad VCA](/quad_vca/)
    - Quad VCA module, original design taken from Ray Wilson from [MFOS](https://musicfromouterspace.com/index.php?MAINTAB=SYNTHDIY&VPW=1697&VPH=669)
        - Log/Linear response

## Power delivery

-  :heavy_check_mark:  [Distribution board](/distribution_b/)
    - Basic Eurorack PSU distribution board, with 12 IDC headers.
-  :warning:  [USB distribution board](/usb_distrib/)
    - Double USB receptacle to power 5V usb devices out of your eurorack case.
-  :warning:  [PSU-Addon](/psu_addon/)
    - Stable +/-12V supply to be plugged after Meanwell RT series PSU    

| Symbol | Description |
| ----------- | ----------- |
| :heavy_check_mark: | Fully designed, debugged, tested, and verified. |
| :warning: | Fully designed but not tested. There is a high chance this won't work first try. |
| :exclamation: | Unfinished, messy design. Do not use, for reference or otherwise. |

![alt text](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License.](http://creativecommons.org/licenses/by-sa/4.0/)

<script src="https://utteranc.es/client.js"
        repo="BleepSound/bleepsound.github.io"
        issue-term="title"
        label="Comment"
        theme="photon-dark"
        crossorigin="anonymous"
        async>
</script>