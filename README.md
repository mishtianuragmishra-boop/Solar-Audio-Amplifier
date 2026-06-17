# Solar-Audio-Amplifier
Photovoltaic cell modelling, power conditioning, and audio amplifier simulation in PSpice.
# Solar Audio Amplifier

A personal engineering project exploring photovoltaic modeling and low-power audio amplification using PSpice.

## Project Goal

Design and simulate a solar-powered audio amplifier by developing photovoltaic circuit models, analyzing their electrical behavior, and integrating them with amplifier stages.

## Progress Log

### Day 1
- Created GitHub repository
- Set up PSpice project environment
- Simulated diode I-V characteristics using DC sweep analysis
- Built a basic solar-cell equivalent circuit using:
  - Current source
  - Diode
- Generated initial photovoltaic response curves
- Documented simulation results
  
Conclusion:
Successfully built and simulated a basic solar-cell model in PSpice. The project setup and initial testing were completed.


- Built the basic single-diode photovoltaic cell model in PSpice.
- Added a photocurrent source and diode.
- Performed DC sweep simulations.
- Generated initial I-V plots.
- Learned how to use simulation profiles and graph outputs in PSpice.

Conclusion:
Successfully created and simulated a basic photovoltaic cell model.

- Added series resistance (Rs) and shunt resistance (Rsh) to the PV model.
- Tested different resistance values and observed their effect on the circuit.
- Connected a load resistor (RL) to create an output terminal.
- Performed an irradiance sweep by varying photocurrent from 0.1 A to 1.0 A.
- Observed output voltage increase from approximately 0.81 V to 0.96 V.

Conclusion:
The PV model responded correctly to increasing irradiance. Higher illumination produced higher output voltage.
## Repository Structure

```
docs/
    Engineering notes and project log
pspice/
    PSpice schematic files
    Simulation files
    Project files
results/
    Screenshots, plots, and analysis results
```
## Current Model
Solar Cell Equivalent Circuit:
```
Photocurrent Source
        ||
        ||
      Diode
        ||
       GND
```
This model serves as the foundation for future photovoltaic simulations.
## Next Steps
- Simulate varying irradiance levels
- Generate solar-cell I-V curves
- Add series and shunt resistance effects
- Analyze power output
- Design amplifier stage
- Integrate photovoltaic source with amplifier load
## Tools
- PSpice
- Git
- GitHub
## Author
Mishti Anurag Mishra
