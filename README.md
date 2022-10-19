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
- One NPN transistor used in the built is the MMBT3904, a SMD version of the 2N3904.
- In order to save space, I am always using small size resistors with values up to 1M, about 3mm length, which are about half the size of usually used resistors.
- On the control board, you will find electrolytic capacitors with a rectangle next to them. Since these capacitors are too tall for standing upright on the board with the main board on top of it, those capacitors need to be mounted in a rectangular position. The rectangle shows the position for each bent-over capacitor.

![WaveFreaker](https://user-images.githubusercontent.com/97026614/196824804-af77b0a8-b712-40ef-9e81-32e5e2864ccc.jpeg)

![WaveFreakerFront](https://user-images.githubusercontent.com/97026614/196824841-a6f6eb17-96d8-45be-8816-dc57368cfec6.jpeg)

![WaveFreakerSide](https://user-images.githubusercontent.com/97026614/196824897-06b14745-d688-454a-bd55-1fa34c149f8b.jpeg)

![WaveFreakerBack](https://user-images.githubusercontent.com/97026614/196824923-6b84e06e-5777-4ddf-9c54-c3c271998109.jpeg)

<img width="374" alt="PCB_MainFront" src="https://user-images.githubusercontent.com/97026614/196825757-bca84748-d627-4e97-ac2c-e567fcc7ed00.png">

<img width="374" alt="PCB_MainBack" src="https://user-images.githubusercontent.com/97026614/196825792-46e12dd5-2b23-42a9-bfc6-9df340f9e28c.png">

<img width="376" alt="PCB_CtrlFront" src="https://user-images.githubusercontent.com/97026614/196825819-9fb4e846-abb8-4a90-b5a3-e87b9a9848fd.png">

<img width="376" alt="PCB_CtrlBack" src="https://user-images.githubusercontent.com/97026614/196825848-ed629668-8dae-4594-af02-d5eb70f20704.png">
