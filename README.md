# Ngspice Code for MOSFET Characterization

This repository contains Ngspice code for simulating and characterizing different types of MOSFETs (Metal-Oxide-Semiconductor Field-Effect Transistors). The repository includes code for depletion NMOS, enhancement NMOS, NMOS and PMOS characteristics, and Pseudo NMOS circuits.

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

This project focuses on simulating and analyzing the characteristics of various MOSFET devices using Ngspice, a popular open-source circuit simulator. MOSFETs are fundamental components in modern integrated circuits, and understanding their behavior is crucial for circuit design and analysis.

## Depletion NMOS

The `Dep-NMOS.cir` file contains Ngspice code for simulating a depletion-type NMOS transistor. The characteristics of depletion NMOS devices, such as drain current vs. drain-source voltage, can be studied using this code.

## Enhancement NMOS

The `Enh-NMOS.cir` file contains code for simulating an enhancement-type NMOS transistor. Enhancement NMOS devices require a threshold voltage to turn on, and this code allows for analysis of their behavior under different bias conditions.

## NMOS Characteristics

The `NMOS_char.cir` file explores the I-V characteristics of a standard NMOS transistor. It includes subcircuits for DC analysis, transfer characteristics, and output characteristics, providing insights into device behavior.

## PMOS Characteristics

The `PMOS_char.cir` file focuses on analyzing the I-V characteristics of PMOS transistors. Similar to the NMOS characteristics code, this file includes subcircuits for DC analysis, transfer characteristics, and output characteristics.

## Pseudo NMOS

The `Pseudo_NMOS.cir` file demonstrates the concept of a Pseudo NMOS circuit, which involves using an NMOS transistor as a pull-up resistor to create a logic gate. This approach is commonly used in low-cost and power-efficient designs.

## Usage

To use the Ngspice code in this repository, follow these steps:

1. Ensure you have Ngspice installed on your system.
2. Clone this repository: `git clone https://github.com/your-username/ngspice-mosfet-characterization.git`
3. Navigate to the specific code file you're interested in.
4. Run the code using Ngspice: `ngspice filename.sp`

## Contributing

Contributions to this project are welcome! If you find any issues or want to add improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code as per the terms of the license.

---

This repository provides Ngspice code for characterizing different types of MOSFETs. Each code file focuses on specific aspects of MOSFET behavior and can be used to gain insights into their characteristics.
