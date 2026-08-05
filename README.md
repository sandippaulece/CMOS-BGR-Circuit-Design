# CMOS-BGR-Circuit-Design
Design and analysis of an Op-Amp assisted CMOS Bandgap Reference (BGR) circuit with PVT, PSRR, and stability analysis.

# CMOS Bandgap Reference Design

## Overview

This project presents the **design and analysis of an Op-Amp assisted CMOS Bandgap Reference (BGR) circuit**. The circuit is designed to generate a stable reference voltage with reduced sensitivity to temperature and supply variations.

The design and simulation were carried out using **Cadence Virtuoso**.

## Objectives

- Design a CMOS BGR operating at **1.8–2.2 V** supply.
- Achieve a reference voltage of approximately **1.25 V**.
- Analyze **PTAT and CTAT** voltage characteristics.
- Perform **Transient, PVT, PSRR, and Stability analysis**.
- Verify the performance of the designed BGR circuit.

## Tools Used

- Cadence Virtuoso
- CMOS Analog IC Design
- Circuit Simulation

## Main Design Blocks

- BGR Core
- Op-Amp
- Startup Circuit
- Schmitt Trigger
- Enable Signal Inverter
- PTAT and CTAT Sections

## Key Results

| Parameter | Result |
|---|---|
| Supply Voltage | 1.8–2.2 V |
| Reference Voltage | 1.248 V |
| Temperature Range | −40°C to 125°C |
| VREF Variation | −0.3% to +2.24% |
| Quiescent Current | 46.9–78 μA |
| Phase Margin | >45° across most corners |
| PSRR | ~−37 dB at 500 kHz |

## Repository Structure

```text
CMOS-Bandgap-Reference-Design/
│
├── README.md
│
├── Design/
│   ├── BGR_Enable_Signal_Inverter_Schematic
│   ├── BGR_OP_Amp_Schematic
│   ├── BGR_Schematic
│   ├── BGR_Startup_Circuit_Schematic
│   └── BGR_Startup_Circuit_Schmitt_Trigger_Circuit_Schematic
│
└── Results/
    ├── BGR_PSRR_Across_PVT_Corners
    ├── BGR_Reference_Voltage_Across_PVT_Corners
    ├── BGR_Reference_Voltage_Transient_Analysis_With_Ringing
    ├── BGR_Reference_Voltage_Transient_Analysis_Without_Ringing
    ├── BGR_Stability_Analysis_Across_PVT_Corners
    └── PTAT_And_CTAT_Voltages_And_Slopes_In_BGR
