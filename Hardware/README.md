# Hardware Design

This directory contains the **circuit schematic and PCB design files together** for the **ESP32-Controlled LC Resonant Pulse Generator**, developed as a group project for the Industrial Electronics course at the University of Tehran.

The hardware was designed, fabricated, assembled, and evaluated in the power electronics laboratory.

## Circuit Schematic

The electronic design integrates the following functional blocks:

- **LC resonant power stage:** Capacitor bank and air-core inductor for resonant current-pulse generation.
- **Power switching:** MOSFET and thyristor switching stages, together with the supporting diode circuitry.
- **Isolated gate driving:** TLP250-based gate-driver circuits with isolated power supplies for switching control.
- **Digital control:** ESP32-based timing and switching-signal generation.
- **Power and interconnections:** Supporting power-supply connections, connectors, and protection components.

The design objective was to produce an approximately sinusoidal current pulse with a **target peak of 60 A** and a **target period of 200 µs**.

## PCB Design and Implementation

The circuit schematic and PCB layout were developed using **Altium Designer**. The PCB brings the resonant power stage, gate-driving circuits, and controller connections together in a single hardware assembly.

Following design and component selection, the PCB was fabricated and assembled for laboratory evaluation.

The project documentation includes the assembled board, its connection to isolated power supplies, and the observed inductor-current waveform.

## Design Files

The **Altium schematic and PCB source files are stored directly in this `Hardware/` directory**

## Related Documentation

- [Hardware Photographs and PCB Visualization](../Images/)
- [Laboratory Demonstration Video](../Demonstration/)
- [Complete Technical Report – PDF](../Report/LC_Resonant_Circuit_Technical_Report.pdf)

**Design Software:** Altium Designer

**Project:** Industrial Electronics – University of Tehran
