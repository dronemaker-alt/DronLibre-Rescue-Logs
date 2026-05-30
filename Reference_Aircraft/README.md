# DronLibre Reference Aircraft Program

## Purpose
The Reference Aircraft Program establishes baseline drones used for teardown, diagnostics, repair, reverse engineering, and recovery procedures.

## Current Aircraft

### DJI Mini
Role:
- Proprietary ecosystem benchmark
- Firmware and diagnostic reference

Planned Structure:
- Photos/
- Hardware_Map/
- Findings.md

### Vivitar Duo-Pro 2
Role:
- Reverse engineering target
- Recovery and repair development platform

Planned Structure:
- Photos/
- Hardware_Map/
- Findings.md

## Findings Numbering System

DL-001 No external service port found
DL-002 Brushless motor architecture confirmed
DL-003 Main MCU identified
DL-004 UART pads located
DL-005 Radio subsystem identified

## Repository Layout

Reference_Aircraft/
├── README.md
├── Initial_Comparison_DJI_Mini_vs_Vivitar_DuoPro2.md
├── DJI_Mini/
│   ├── Photos/
│   ├── Hardware_Map/
│   └── Findings.md
│
├── Vivitar_DuoPro2/
│   ├── Photos/
│   ├── Hardware_Map/
│   └── Findings.md
│
└── Hardware_Maps/

## Engineering Philosophy
Document findings as repeatable observations. Record evidence, photographs, hardware identification, interfaces, and recovery methods. Build a reusable knowledge base for future drone rescue and reverse-engineering efforts.