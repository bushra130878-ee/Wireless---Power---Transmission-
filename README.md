# Wireless Power Transmission System

## Overview
This project demonstrates the principle of wireless power transfer 
using inductive (electromagnetic) coupling between two coils. The 
system was designed and simulated in Proteus, showcasing how electrical 
energy can be transmitted without any direct wired connection between 
the source and the load.

## Components Used
- 9V Battery (power source)
- Transistor 2N2222A (oscillator circuit)
- Resistor – 27kΩ
- Transmitter coil (L3) – 100µH
- Receiver coil (L4) – 100µH
- LED (green) – load indicator

## Working Principle
- A transistor-based oscillator circuit drives current through the 
  transmitter coil, generating a rapidly alternating magnetic field.
- The receiver coil, placed in proximity to the transmitter, captures 
  this changing magnetic field through electromagnetic induction.
- The induced current in the receiver coil powers the connected LED, 
  causing it to glow wirelessly — with no physical wire linking the 
  two circuits.

## Result
The simulation successfully verified wireless power transfer: the LED 
lit up solely from the energy induced in the receiver coil, confirming 
the core principle behind technologies like wireless charging pads and 
contactless power systems.

## Applications & Future Scope
This principle forms the foundation of real-world technologies such as 
wireless phone chargers, RFID systems, and biomedical implant charging. 
The circuit can be scaled up with improved coil design and resonant 
tuning to transfer higher power levels for practical devices.

## Files in this Repository
- Circuit schematic and simulation
