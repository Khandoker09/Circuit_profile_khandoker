---
title: circuit project
layout: page
---

## 1. Mapping of Mammalian Purkinje Network on an Electrically Equivalent Circuit
![PCB Front Image](https://github.com/Khandoker09/Circuit_profile_khandoker/blob/main/project/purkinji%20circuit/schematic.PNG)
The circuit simulation was conducted using cable theory to analyze the delay signal in the heart's response, which is influenced by factors beyond just electrical conduction. A 10 Hz single frequency signal with 1 volt (peak to peak) amplitude was inputted via a frequency generator. In normal conditions, the heart's pulse propagates with a 0.6 volt (peak to peak) signal, and although there is no ground connection in reality, a common ground was added for simulation purposes. Blocks were added in place of Purkinje cells, and the output was observed from each block to measure conduction delay.

![PCB](https://github.com/Khandoker09/Circuit_profile_khandoker/blob/main/project/purkinji%20circuit/3d%20pb.PNG)

Electrical blocks were cascaded to facilitate pulse propagation between cells, with voltage control voltage gates used to continue propagation to the next segment. Resistor and capacitor values were carefully chosen to determine conduction delay, with 100 ohm resistors selected for extracellular membrane and 1 ohm resistors for intracellular space, along with 10 microfarad capacitors for membrane capacitance. Notably, the simulation did not consider the electrical conduction of muscle tissue.



## 2. Crosstalk Simulation

In electronic systems, crosstalk refers to the phenomenon where signals unintentionally interfere with each other due to coupling between adjacent conductors or components. This interference can degrade the integrity and quality of signals, leading to errors or malfunctioning of the system. Understanding and mitigating crosstalk is crucial in ensuring the reliable operation of electronic devices and circuits.

![Near-End Crosstalk Simulation](https://github.com/Khandoker09/Circuit_profile_khandoker/blob/main/project/cstcrosstalk/ck.PNG)
There are two main types of crosstalk: near-end crosstalk (NEXT) and far-end crosstalk (FEXT). 

- **Near-End Crosstalk (NEXT):** NEXT occurs when the interfering signal originates from a source near the receiving end of the affected conductor. It typically arises due to capacitive or inductive coupling between adjacent conductors within a cable or on a printed circuit board (PCB).

- **Far-End Crosstalk (FEXT):** FEXT, on the other hand, occurs when the interfering signal originates from a source farther away from the receiving end. This type of crosstalk is often caused by electromagnetic coupling between adjacent conductors over longer distances.

To analyze and understand the impact of crosstalk on signal integrity, simulations are conducted using specialized software such as CST (Computer Simulation Technology). These simulations allow engineers to visualize and quantify the extent of crosstalk in electronic systems, enabling them to design effective countermeasures to minimize its effects.
![Far-End Crosstalk Simulation](https://github.com/Khandoker09/Circuit_profile_khandoker/blob/main/project/cstcrosstalk/cksim.PNG)
In this project, crosstalk simulations using CST will be performed to demonstrate both near-end and far-end crosstalk. By visualizing and analyzing the simulated results, insights into the behavior of crosstalk and its implications for system performance will be gained, facilitating the development of strategies to mitigate its adverse effects.

## 3. FM Transmitter Design Using EasyEDA

![3D PCB Visualization](https://github.com/Khandoker09/Circuit_profile_khandoker/blob/main/project/fm%20tranmmitter/3dfmtransmit.PNG)
An FM (Frequency Modulation) transmitter is a crucial component in wireless communication systems, allowing the transmission of audio signals over radio frequencies. Designing a reliable and efficient FM transmitter requires careful consideration of various factors such as frequency stability, signal purity, and power efficiency.

In this project, we will utilize EasyEDA, a user-friendly online PCB design tool, to create a high-quality FM transmitter circuit. EasyEDA provides a seamless platform for schematic capture, PCB layout design, and simulation, making it ideal for both novice and experienced electronics enthusiasts.

The FM transmitter design will involve selecting appropriate components such as oscillators, modulators, and amplifiers to generate a stable carrier signal and modulate it with the desired audio input. Additionally, considerations will be made to ensure the design is compact, cost-effective, and compatible with standard FM radio receivers.

One of the advantages of using EasyEDA is its integrated 3D PCB visualization feature, which allows us to preview the final PCB design in a realistic three-dimensional environment. This enables us to assess component placement, trace routing, and overall aesthetics before proceeding with fabrication.

By leveraging the capabilities of EasyEDA and incorporating best practices in RF circuit design, we aim to develop a functional FM transmitter that meets performance requirements and serves as a valuable learning experience for electronics enthusiasts.

### 4. USB-C to 5V DC Power Converter
![3dpcb](https://github.com/Khandoker09/Circuit_profile_khandoker/blob/main/project/usbc%20to%205%20volt/3d_usbc_5v.PNG)
This project aims to design a USB-C to 5V DC power converter, allowing for the conversion of power from a USB-C power source to a stable 5V output. The converter consists of a USB-C connector, a power management IC (PMIC) capable of handling USB Power Delivery (PD) negotiation, and supporting passive components such as capacitors and resistors. The design process involves schematic design, PCB layout, prototype assembly, testing, and optimization. By following industry standards and best practices, the converter ensures efficient and reliable power conversion for various electronic devices.


