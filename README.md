# Solar Audio Amplifier

A personal electronics and power-systems engineering project focused on designing a solar-powered audio amplifier from the ground up. The project combines photovoltaic modelling, power conditioning, energy conversion, and audio amplification using circuit simulation tools.

---

## Project Overview

The objective is to design a complete low-power audio system powered by a photovoltaic source.

The project is divided into four major subsystems:

1. Photovoltaic Cell Modelling
2. Power Conditioning and Voltage Conversion
3. Audio Amplifier Design
4. System Integration and Performance Analysis

All development is currently being performed through circuit simulation before hardware implementation.

---

## Current Progress

### Phase 1 – Photovoltaic Modelling ✅

Completed development of a photovoltaic equivalent circuit model using:

* Photocurrent source
* Diode model
* Series resistance (Rs)
* Shunt resistance (Rsh)
* Variable load resistance

Activities completed:

* Built a basic single-diode solar-cell model
* Performed DC sweep simulations
* Generated I-V characteristics
* Investigated effects of irradiance variation
* Studied effects of series and shunt resistance
* Verified expected photovoltaic behaviour

Key observations:

* Increased irradiance increased output voltage and current
* Series resistance reduced output performance
* Shunt resistance affected leakage behaviour
* Simulated results matched expected solar-cell characteristics

---

### Phase 2 – Power Conditioning ✅

Developed and validated a boost-converter stage intended to increase photovoltaic output voltage for downstream circuitry.

Converter topology:

* Input source
* Inductor
* MOSFET switch
* Schottky diode
* Output capacitor
* Load resistor

Activities completed:

* Initial design in PSpice
* Migration to LTspice for debugging and validation
* Replacement of generic switching components with realistic models
* Verification of switching behaviour
* Observation of boost-converter voltage step-up operation
* Analysis of inductor current and output voltage response

Simulation results demonstrated:

* Successful voltage boosting above source voltage
* Expected switching waveforms
* Proper energy transfer through the inductor-diode network
* Stable converter operation after component adjustments

---

### Phase 3 – Audio Amplifier Design 🔄

Planned work:

* Small-signal amplifier stage
* Power amplification stage
* Input coupling and filtering
* Bias network design
* Gain analysis
* Frequency response characterization

---

### Phase 4 – System Integration ⏳

Future work:

* Connect photovoltaic model to boost converter
* Connect boost converter to amplifier stage
* Evaluate overall efficiency
* Investigate noise and ripple effects
* Simulate varying irradiance conditions
* Analyze real-world operating scenarios

---

## Simulation Tools

### PSpice

Used for:

* Initial photovoltaic modelling
* DC sweep analysis
* Early-stage circuit development

### LTspice

Used for:

* Power electronics simulation
* Boost converter validation
* Switching waveform analysis
* Circuit debugging

### Git & GitHub

Used for:

* Version control
* Engineering documentation
* Progress tracking
* Design archiving

---

## Repository Structure

```text
docs/
    Engineering notes
    Daily progress logs
    Design documentation

pspice/
    PSpice schematics
    Project files
    Simulation profiles

ltspice/
    LTspice schematics
    Converter validation files

results/
    Plots
    Screenshots
    Analysis figures
```

---

## Current Status

| Subsystem                  | Status      |
| -------------------------- | ----------- |
| Solar Cell Model           | Complete    |
| Irradiance Analysis        | Complete    |
| PV Characterization        | Complete    |
| Boost Converter Design     | Complete    |
| Boost Converter Validation | Complete    |
| Audio Amplifier Design     | In Progress |
| System Integration         | Pending     |

---

## Project Goal

Design a fully simulated solar-powered audio amplifier system capable of converting photovoltaic energy into amplified audio output through an integrated power-conditioning stage.

---

## Author

Mishti Anurag Mishra
