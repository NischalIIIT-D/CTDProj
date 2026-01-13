# CTDProj

## 3rd-Order Active Butterworth Low-Pass Filter (12 dB Gain)

This repository contains the complete design and implementation of a 3rd-order active Butterworth low-pass filter with a 12 dB flat-band gain, realized using LM741 operational amplifiers. The filter is implemented by cascading a first-order active low-pass stage with a second-order Sallen-Key low-pass stage to achieve a maximally flat passband response and a steep roll-off.

The project covers the entire hardware design flow, including analytical calculations, circuit simulation, PCB design, fabrication, soldering, and experimental validation.

### Project Specifications

Filter Type: Active Low-Pass Butterworth

Order: 3

Flat-Band Gain: ~12 dB

Cutoff Frequency: ~1 kHz

Topology:

Stage A: First-order active low-pass

Stage B: Second-order Sallen-Key low-pass

Operational Amplifier: LM741

Supply Voltage: ±12 V

PCB: Single-layer, through-hole, DRC-compliant

### Design Methodology

Theoretical Design

Butterworth approximation for maximally flat passband

Gain distribution across stages

Cutoff frequency calculations

Simulation

AC frequency response analysis using LTspice

Verification of gain, cutoff frequency, and roll-off slope

PCB Design

Schematic capture and layout using KiCad

Single-layer PCB with no vias

Routing performed under strict DRC constraints (minimum track width, clearance, and edge spacing)

Fabrication and Assembly

PCB fabricated using generated Gerber files

Manual soldering of all through-hole components

Testing and Validation

Hardware testing using a function generator and oscilloscope

Measurement of flat-band gain, cutoff frequency, and roll-off

Comparison of experimental results with LTspice simulation

### Results

Achieved approximately 12 dB flat-band gain

Measured cutoff frequency close to the design target

Observed roll-off consistent with a 3rd-order low-pass response (~60 dB/decade)

Hardware measurements showed good agreement with simulation trends
