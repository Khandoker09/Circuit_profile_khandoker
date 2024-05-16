---
title: circuit project
layout: page
---

## Mapping of Mammalian Purkinje Network on an Electrically Equivalent Circuit
![PCB Front Image](https://github.com/Khandoker09/Circuit_profile_khandoker/blob/main/project/purkinji%20circuit/schematic.PNG)
The circuit simulation was conducted using cable theory to analyze the delay signal in the heart's response, which is influenced by factors beyond just electrical conduction. A 10 Hz single frequency signal with 1 volt (peak to peak) amplitude was inputted via a frequency generator. In normal conditions, the heart's pulse propagates with a 0.6 volt (peak to peak) signal, and although there is no ground connection in reality, a common ground was added for simulation purposes. Blocks were added in place of Purkinje cells, and the output was observed from each block to measure conduction delay.

![PCB](https://github.com/Khandoker09/Circuit_profile_khandoker/blob/main/project/purkinji%20circuit/3d%20pb.PNG)

Electrical blocks were cascaded to facilitate pulse propagation between cells, with voltage control voltage gates used to continue propagation to the next segment. Resistor and capacitor values were carefully chosen to determine conduction delay, with 100 ohm resistors selected for extracellular membrane and 1 ohm resistors for intracellular space, along with 10 microfarad capacitors for membrane capacitance. Notably, the simulation did not consider the electrical conduction of muscle tissue.



