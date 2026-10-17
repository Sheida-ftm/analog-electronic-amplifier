# Analog Amplifier Design

A transistor-based analog amplifier designed as the final project for the **Electronics II** course. The project involved designing, analyzing, and optimizing a multi-stage amplifier to satisfy a predefined set of electrical specifications using analytical calculations and LTspice simulations.

---

## Project Overview

The objective of this project was to design a complete analog amplifier rather than individual circuit blocks. The design process emphasized engineering analysis, proper transistor biasing, gain distribution, stability, and performance optimization while satisfying the required design specifications.

The amplifier was developed using a structured, two-phase design methodology consisting of analytical design followed by simulation-based optimization.

---

## Design Architecture

The amplifier consists of the following functional blocks:

- Input amplification stage
- Intermediate gain stage(s)
- Output stage
- Biasing network
- Negative feedback network

Each block was designed to contribute to the amplifier's overall performance while ensuring stable operation and meeting the required specifications.

---

## Design Process

### Phase I – Initial Design

- Selected the amplifier topology
- Designed transistor biasing networks
- Performed DC operating point analysis
- Derived small-signal models
- Calculated voltage gain and impedance values
- Sized circuit components using analytical calculations

### Phase II – Optimization

The initial design was refined using LTspice simulations by optimizing:

- Voltage gain
- Frequency response
- Output swing
- Bias stability
- Power consumption
- Load-driving capability
- Overall circuit performance

---

## Analyses Performed

The final design was verified through multiple simulation and analysis techniques, including:

- DC Operating Point Analysis
- AC Small-Signal Analysis
- Frequency Response (Bode Plot)
- Transient Analysis
- Output Swing Verification
- Load Analysis
- Bias Verification
- Stability Analysis

---

## Performance Evaluation

The amplifier was evaluated according to several important analog design metrics:

- Midband voltage gain
- Bandwidth
- Low- and high-frequency cutoff frequencies
- Input impedance
- Output impedance
- Output voltage swing
- Power consumption
- Total Harmonic Distortion (THD)
- Power Supply Rejection Ratio (PSRR)
- Stability under varying load conditions

---

## Tools Used

- **LTspice** for circuit simulation
- Small-signal transistor analysis
- Hand calculations for analytical verification

---

## Repository Structure

```
.
├── Calculations/          # Design calculations
├── LTspice/               # LTspice schematics and simulation files
├── Results/               # Simulation plots and outputs
├── Report/                # Project report
└── README.md
```

---

## Key Learning Outcomes

This project provided practical experience in:

- Multi-stage analog amplifier design
- Transistor biasing techniques
- Small-signal circuit analysis
- Frequency response analysis
- Negative feedback implementation
- Analog circuit optimization
- Simulation-based verification
- Engineering design methodology

---

## Author

**Sheida Fatemizadeh**

Electrical Engineering Undergraduate  
Sharif University of Technology
