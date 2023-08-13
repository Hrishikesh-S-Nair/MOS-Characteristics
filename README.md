# Ngspice Code for MOSFET Characterization

Welcome to the Ngspice Code for MOSFET Characterization repository. This project focuses on simulating and characterizing various types of MOSFETs (Metal-Oxide-Semiconductor Field-Effect Transistors) using Ngspice, an open-source circuit simulator. MOSFETs are essential components in modern integrated circuits, and understanding their behavior is critical for circuit design and analysis.

## Contents

1. [Introduction](#introduction)
2. [Depletion NMOS](#depletion-nmos)
3. [Enhancement NMOS](#enhancement-nmos)
4. [NMOS Characteristics](#nmos-characteristics)
5. [PMOS Characteristics](#pmos-characteristics)
6. [Pseudo NMOS](#pseudo-nmos)
7. [Usage](#usage)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

This repository provides a comprehensive exploration of MOSFETs through Ngspice simulations. MOSFETs play a pivotal role in modern electronics, serving as switches and amplifiers. By simulating different types of MOSFETs, this project aims to deepen your understanding of their behavior in various circuit configurations.

## Depletion NMOS

The `Dep-NMOS.cir` file contains Ngspice code dedicated to simulating a depletion-mode NMOS transistor. Depletion NMOS devices exhibit unique behavior due to their intrinsic threshold voltage. Through this simulation, you can investigate key characteristics, such as the drain current versus drain-source voltage relationship.

![N-channel-depletion-mode-MOSFET](https://github.com/Hrishikesh-S-Nair/MOS-Characteristics/assets/125496407/82c0c277-3a1f-4752-9768-f8a330b83037)


## Enhancement NMOS

Explore the `Enh-NMOS.cir` file to delve into the world of enhancement-mode NMOS transistors. Unlike their depletion-mode counterparts, enhancement NMOS devices require a threshold voltage to turn on. By analyzing this simulation, you can gain insights into how enhancement NMOS transistors respond to different bias conditions.

![n_channel_mosfet_enhancement](https://github.com/Hrishikesh-S-Nair/MOS-Characteristics/assets/125496407/bede4040-f1cb-4bfd-9813-cdde847f1162)

## NMOS Characteristics

The `NMOS_char.cir` file offers a comprehensive analysis of the I-V characteristics of a standard NMOS transistor. The simulation covers essential aspects such as DC analysis, transfer characteristics, and output characteristics. By running this simulation, you can unravel the intricate relationship between various terminal voltages and currents in an NMOS device.

![Deflection-mode copy](https://github.com/Hrishikesh-S-Nair/MOS-Characteristics/assets/125496407/7d0e5a42-159f-4f22-a1a4-e14cbea4cee4)

## PMOS Characteristics

Uncover the characteristics of PMOS transistors in the `PMOS_char.cir` file. Similar to the NMOS characteristics simulation, this code examines the I-V behavior of PMOS devices. This comprehensive analysis includes DC analysis, transfer characteristics, and output characteristics, providing insights into the complexities of PMOS operation.

![Deflection-mode](https://github.com/Hrishikesh-S-Nair/MOS-Characteristics/assets/125496407/1e2bbba7-247a-44cc-bcb3-15f24bfda65f)

## Pseudo NMOS

Dive into the concept of Pseudo NMOS circuits with the `Pseudo_NMOS.cir` file. A Pseudo NMOS design involves using an NMOS transistor as a pull-up resistor to create a logic gate. This approach is known for its simplicity, cost-effectiveness, and power efficiency. By simulating this circuit, you can grasp the mechanics of how a Pseudo NMOS design functions.

![maxresdefault](https://github.com/Hrishikesh-S-Nair/MOS-Characteristics/assets/125496407/531718b2-9a86-4cfa-85cd-9113295430dd)

## Usage

To explore the Ngspice simulations in this repository, follow these steps:

1. Ensure that you have Ngspice installed on your system.
2. Clone this repository to your local machine: `git clone https://github.com/your-username/ngspice-mosfet-characterization.git`
3. Navigate to the specific simulation file you are interested in.
4. Run the simulation using Ngspice: `ngspice filename.sp`

## Contributing

Contributions to this project are highly encouraged! Whether you find issues or have ideas for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You have the freedom to use, modify, and distribute the code according to the terms of the license mentioned above.

