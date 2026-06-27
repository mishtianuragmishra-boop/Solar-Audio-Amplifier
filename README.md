# Solar-Powered Two-Stage BJT Audio Amplifier

## Overview

This project presents the design, simulation, and analysis of a solar-powered two-stage BJT audio amplifier using **LTspice**. The objective was to investigate whether a photovoltaic source could be used to power a transistor amplifier capable of amplifying an audio signal and driving a low-impedance speaker.

The project focuses on understanding transistor biasing, voltage amplification, current amplification, AC coupling, and systematic analog circuit debugging rather than producing a high-power commercial amplifier.

---

# Objectives

* Design a solar-powered analog amplifier.
* Model a photovoltaic source using an equivalent circuit.
* Implement a two-stage BJT amplifier.
* Verify correct transistor biasing.
* Amplify a 1 kHz audio signal.
* Investigate the behaviour of the amplifier when driving an 8 Ω speaker.
* Analyze the limitations of a single-transistor output stage.

---

# Circuit Description

The amplifier consists of the following sections:

### Solar Source

* Photocurrent source
* Diode equivalent model
* Series resistance
* Shunt resistance

This provides the DC supply required to operate the amplifier.

### First Stage (Q1)

A common-emitter amplifier using a BJT provides voltage gain.

Functions:

* Signal amplification
* DC bias stabilization
* Initial voltage gain

### Second Stage (Q2)

An emitter follower acts as the output stage.

Functions:

* Current amplification
* Low output impedance
* Speaker interface

### Output Coupling

A coupling capacitor isolates the speaker from DC while allowing AC audio signals to pass.

---

# Simulation

All simulations were performed using **LTspice**.

The following analyses were carried out:

* DC Operating Point (.op)
* Transient Analysis (.tran)
* Waveform Observation
* Component Optimization

---

# Results

The completed circuit demonstrated:

* Successful photovoltaic power modelling
* Stable transistor biasing
* Voltage amplification in the first stage
* Current buffering in the second stage
* Successful transfer of an AC signal to an 8 Ω load

During testing, numerous resistor values, transistor models, supply voltages, and coupling configurations were investigated to understand their effect on amplifier performance.

The project also highlighted the importance of operating-point analysis before transient simulation and demonstrated the role of coupling capacitors in preventing DC current from reaching the speaker.

---

# Key Engineering Observations

* Proper transistor biasing is essential for analog amplifier operation.
* Common-emitter amplifiers provide voltage gain.
* Emitter followers primarily provide current gain.
* Coupling capacitors block DC while passing AC signals.
* Operating-point analysis and transient analysis provide different but complementary information.
* Low-impedance speakers require significantly more output current than a simple emitter follower can efficiently provide.

---

# Limitations

The amplifier successfully amplified the input signal and delivered AC current to the speaker; however, the single-transistor emitter follower output stage was unable to efficiently drive an 8 Ω loudspeaker at high output power.

Future improvements include:

* Complementary push-pull output stage
* Class-AB output stage
* Darlington output stage
* Improved power efficiency
* PCB implementation
* Hardware prototype using a real photovoltaic panel

---

# Skills Demonstrated

* Analog circuit design
* LTspice simulation
* BJT biasing
* Small-signal amplifier design
* Solar-cell equivalent modelling
* Operating-point analysis
* Transient analysis
* Waveform interpretation
* Analog circuit debugging
* Engineering documentation

---

# Tools Used

* LTspice
* Bipolar Junction Transistors (BC547B / 2N2222 during testing)
* Equivalent Solar Cell Model
* Passive Components (Resistors, Capacitors)
* 8 Ω Speaker Load

---

# Lessons Learned

This project demonstrated that designing an analog amplifier involves far more than assembling components. Correct biasing, operating-point verification, waveform interpretation, and iterative debugging were all critical to obtaining a functional circuit.

The investigation also reinforced the distinction between voltage amplification and power amplification, illustrating why practical audio amplifiers employ dedicated output stages when driving low-impedance loads.

---

# Author

MISHTI ANURAG MISHRA

Personal Analog Electronics Project – 2026
