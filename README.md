# EurorackWaveFreaker
## General
A Wave Folder Eurorack module, based on the design from Music From Outer Space.
The module contains two folding modes, a step-shape option, and two sub-oscillators (one and two octaves).

## Module Built and PCBs
If you want to build the module yourself, I uploaded the schematic, the BOM and the Gerber files for the PCBs.

I used SMD components only for bypass caps. All other components are through-hole.

There are two different versions for the control board, an "original" and a "Thonk" version.
Reason is that for my own module, I am using specific potentiometers - 16K4 series from Supertech Electronics - and 3.5mm jack sockets - MJ-355 from Marushin - available at my local electronics shop.

However, since most DIY projects for Eurorack modules out there are using potentiometers from ALPHA and so-called THONKICONN jacks, as they are provided by Thonk in the UK, I also created a version with footprints for those components.
Choose the one you need.

I created the Gerber files with the online tool EasyEDA and ordered it at JLCPCB.
I cannot guarantee, if this set of zipped Gerber files works also for other providers, like e.g. PCBWay. I have not tried that. But I saw online, that others did it.

If you want to know about my DIY building process, take a look at those two YouTube videos:
- [How I design PCBs for my Eurorack Synth Modules](https://youtu.be/pXtuV9Pv-m4)
- [Eurorack Module Synth - Building an Electric Druid Wavetable Oscillator Module](https://youtu.be/ECpdo4HfqLg)

## Panel Layout
I added the information about hole coordinates for the front panel in the folder PanelLayout, refering to the component layout in the Gerber files. The layout is the same for both versions.

## Additional Information about specific Components
If you want to use the Gerber files for having PCB manufactured, please note the following information about components used.

- There is a number of SMD 0.1uF capacitors with the package size 1608.
- In order to save space, I am always using small size resistors with values up to 1M, about 3mm length, which are about half the size of usually used resistors.
- On the control board, you will find electrolytic capacitors with a rectangle next to them. Since these capacitors are too tall for standing upright on the board with the main board on top of it, those capacitors need to be mounted in a rectangular position. The rectangle shows the position for each bent-over capacitor.

![WaveFreaker](https://user-images.githubusercontent.com/97026614/196673312-ec7c86c4-cae0-4d6d-a0f6-af58e2b0724e.jpeg)

![WaveFreakerFront](https://user-images.githubusercontent.com/97026614/196673413-07068c2b-2faa-49b5-ac59-6c3799b8bdc2.jpeg)

![WaveFreakerSide](https://user-images.githubusercontent.com/97026614/196673456-04d2461a-c41b-4336-baeb-3120d0924e58.jpeg)

![WaveFreakerBack](https://user-images.githubusercontent.com/97026614/196673591-0538da9f-d967-4c33-a2dc-f3fc04577477.jpeg)
