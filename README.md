---
permalink: /index.html
layout: single
---

# Bleep Sound Eurorack modules

## Not all projects are finished or even perfect, use at your own risks.

### Filters:

- MS20-VCF
    - MS-20 clones built around the LM13700 chip
    - :heavy_check_mark: [Simple MS20 VCF](ms20-vcf-simple):
        - 1 LM13700 filter with a Low pass or High pass switch with CV for cutoff
        - Based on barton's version : <https://www.bartonmusicalcircuits.com/synthstuff.html#analog>
    - :heavy_check_mark: [Double MS20-VCF](ms20-vcf-double)
        - 2 filters in one, each with Low pass or High pass with a possibility to bridge them and get a band pass filter with CV for cutoff
        - Based on barton's version (https://www.bartonmusicalcircuits.com/synthstuff.html#analog))

### Mixers:

- :heavy_check_mark: [Basic DC mixer](basic-mixer-dc)
    - 4 channel active mixer with mute option with DC coupling (Audio+CV)

### VCOs:

- :heavy_check_mark: [RP2040 chord VCO](rp2040-chord-vco)
    - VCO clone, originally made by HAGIWO ([link](https://note.com/solder_state/n/n64b91a171218) in japanese)
    - RP2040 chord VCO clone in SMD.
    - 5-polyphonic Chord VCO module. There are 8 types of tones. With a built-in quantizer and automatic harmonics function, if you input a suitable CV, it will play a nice chord progression.

| Symbol | Description |
| ----------- | ----------- |
| :heavy_check_mark: | Fully designed, debugged, tested, and verified. |
| :warning: | Fully designed but not tested. There is a high chance this won't work first try. |
| :exclamation: | Unfinished, messy design. Do not use, for reference or otherwise. |

*Cheers to @Sonosus for the labeling idea*

![alt text](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License.](http://creativecommons.org/licenses/by-sa/4.0/)
