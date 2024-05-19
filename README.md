# Complete ASIC Flow of PIT (Programmable Interrupt Timer)

## Overview

This project encompasses the entire ASIC design flow for a Programmable Interrupt Timer (PIT) using SAED90nm technology and Synopsys tools. It includes RTL design, synthesis, simulation, verification, and physical design steps necessary to implement a fully functional PIT module in hardware.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Directory Structure](#directory-structure)
4. [Dependencies](#dependencies)
5. [License](#license)

   
## Introduction

The Programmable Interrupt Timer (PIT) is a critical component in many embedded systems, providing precise timing and interrupt capabilities. This repository demonstrates a complete Application-Specific Integrated Circuit (ASIC) design flow for a PIT, from high-level RTL design to the final physical layout.

## Features

- **RTL Design:** Verilog-based RTL implementation of the PIT.
- **Synthesis:** Conversion of RTL code to gate-level representation using Synopsys Design Compiler (DC).
- **Formal Verification:** Verification using Synopsys Formality.
- **Physical Design:** Floorplanning, placement, routing, and sign-off checks using Synopsys ICC II.
- **Timing Analysis:** Detailed timing analysis using Synopsys PrimeTime.

## Directory Structure

```plaintext
Complete-ASIC-Flow-of-PIT-Programmable-Interrupt-Timer/
│
├── ASIC Project/           # Master folder for the project
│   ├── Syn/                # Synthesis scripts and results (Synopsys Design Compiler)
│   ├── pnr/                # Physical design files (Synopsys ICC II)
│   ├── RTL/                # RTL design files
│   ├── ndm/                # Floorplanning files
│   ├── PrimeTime/          # Timing analysis files (Synopsys PrimeTime)
│   ├── fm/                 # Formal verification files (Synopsys Formality)
│   └── scripts/            # Utility scripts
│
└── README.md               # This README file
```

## Dependencies
### This project requires the following tools:

- **Verilog Simulator:** ModelSim, VCS, or equivalent
- **Synthesis Tool:** Synopsys Design Compiler
- **Formal Verification Tool:** Synopsys Formality
- **Physical Design Tool:** Synopsys ICC II
- **Timing Analysis Tool:** Synopsys PrimeTime

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
