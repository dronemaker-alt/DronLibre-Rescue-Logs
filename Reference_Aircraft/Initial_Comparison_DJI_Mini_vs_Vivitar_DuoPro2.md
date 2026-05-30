# DronLibre Engineering Notes
## Initial Aircraft Comparison
### DJI Mini vs Vivitar Duo-Pro 2

**Date:** 2026-05-30

## Purpose
Establish baseline comparison between two DronLibre reference aircraft representing proprietary and consumer-market drone architectures.

## Reference Aircraft

### Aircraft 001 - DJI Mini
Status:
- Powers up
- Camera self-test operational
- Gimbal operational
- USB-C interface present

Role:
- Proprietary ecosystem reference aircraft
- Firmware and diagnostic target

### Aircraft 002 - Vivitar Duo-Pro 2
Status:
- Powers up
- Brushless motors installed
- No external programming/service port identified

Role:
- Consumer-market recovery and reverse-engineering target

## Physical Comparison
- Similar overall footprint
- Similar motor spacing
- Rear battery insertion on both aircraft
- Folding arm architecture on both aircraft

## Folding Mechanism Comparison

### DJI Mini
- Rear arms pivot down and under fuselage
- More compact folded package
- Higher mechanical complexity

### Vivitar Duo-Pro 2
- Rear arms fold inward only
- Simpler hinge geometry
- Potentially more durable for repeated deployment cycles
- Easier field repair

### Initial Assessment
The Duo-Pro 2 folding mechanism appears mechanically more robust and may better tolerate repeated folding and unfolding than the DJI Mini design.

## Serviceability Comparison

### DJI Mini
Accessible interfaces:
- USB-C
- Data connection
- Charging interface

### Vivitar Duo-Pro 2
Accessible interfaces:
- Battery compartment
- Power switch
- Camera assembly

Finding DL-001:
No external programming or service interface identified.

Implication:
Likely utilizes internal UART, SWD, JTAG, manufacturing test pads, or proprietary programming fixture.

## Motor System
Both aircraft utilize brushless direct-drive motors.

Observation:
The Duo-Pro 2 is not a toy-grade brushed aircraft and appears to use a conventional brushless flight-control architecture.

## DronLibre Assessment
DJI Mini:
- Diagnostic development
- Firmware analysis
- Log recovery

Vivitar Duo-Pro 2:
- Reverse engineering
- Hardware identification
- Board mapping
- Recovery methodology development

## Next Actions
1. Exterior documentation
2. Fastener mapping
3. Controlled teardown
4. Main board photography
5. MCU identification
6. Radio subsystem identification
7. Search for UART/SWD/JTAG access points
8. Build first DronLibre hardware map

## Conclusion
The DJI Mini serves as the proprietary benchmark aircraft. The Vivitar Duo-Pro 2 serves as the first dedicated reverse-engineering target for the DronLibre project.