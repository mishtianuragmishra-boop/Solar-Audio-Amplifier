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
