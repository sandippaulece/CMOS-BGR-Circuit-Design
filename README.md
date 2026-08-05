# CMOS-BGR-Circuit-Design
Design and analysis of an Op-Amp assisted CMOS Bandgap Reference (BGR) circuit with PVT, PSRR, and stability analysis.

# CMOS Bandgap Reference Design

## 📌 Project Overview

This project presents the **design and analysis of an Op-Amp assisted CMOS Bandgap Reference (BGR) circuit**. The circuit is designed to generate a stable reference voltage with reduced sensitivity to supply voltage and temperature variations.

The design and simulations were carried out using **Cadence Virtuoso**.

## 🎯 Objectives

* Design a CMOS Bandgap Reference operating at **1.8–2.2 V** supply.
* Generate a reference voltage of approximately **1.25 V**.
* Analyze **PTAT and CTAT** voltage characteristics.
* Perform **Transient, DC, PSRR, and PVT analysis**.
* Verify the stability of the BGR circuit.

## 🛠️ Tools Used

* **Cadence Virtuoso**
* CMOS Analog IC Design
* Circuit Simulation and Analysis

## 🔧 Main Components

* CMOS current mirrors
* PNP BJTs
* PTAT and CTAT branches
* Operational amplifier
* Startup circuit
* Schmitt trigger
* Enable inverter

## 📊 Key Results

* Typical reference voltage: **1.248 V**
* Supply voltage: **1.8–2.2 V**
* Temperature range: **−40°C to 125°C**
* VREF variation: **−0.3% to +2.24%**
* Quiescent current: **46.9–78 μA**
* Phase margin: **>45°** across most corners
* PSRR: approximately **−37 dB at 500 kHz**

## 📁 Repository Structure

```text
CMOS-Bandgap-Reference-Design/
│
├── README.md
├── Design/
├── Simulation_Results/
├── Images/
└── Project_Report.pdf
```

## 👥 Authors

* Rito Gupta
* Ranadip Das
* Sandip Paul

**Department of Electronics and Communication Engineering**
Heritage Institute of Technology, Kolkata

## 📄 Project Report

The complete project report is included in this repository for detailed information about the design, simulation, and analysis.
