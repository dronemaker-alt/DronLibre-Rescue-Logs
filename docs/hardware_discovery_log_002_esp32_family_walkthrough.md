# DronLibre Hardware Discovery Log 002
## ESP32 Family Identification and Recovery Session

Date: 2026-05-30

### Objective

Identify and catalog ESP32-family development boards recovered from project inventory.

---

## Board 001 - ESP32 Dev Board

### Interface
- USB Serial
- COM10

### Identification Results

Chip Type:
ESP32-D0WD-V3

Features:
- WiFi
- Bluetooth
- Dual Core
- LP Core
- 240 MHz

Crystal:
40 MHz

MAC Address:
e4:65:b8:83:20:a8

Flash:
- Manufacturer: 5e
- Device: 4016
- Flash Size: 4 MB

Status:
Operational

---

## Board 002 - LilyGO ESP32-S3

### Interface
- USB Serial/JTAG
- COM11

### Identification Results

Chip Type:
ESP32-S3 (QFN56)

Features:
- WiFi
- Bluetooth 5 LE
- Dual Core
- LP Core
- Embedded PSRAM
- USB Serial/JTAG

Crystal:
40 MHz

MAC Address:
80:65:99:a1:64:3c

Flash:
- Manufacturer: ef
- Device: 4018
- Flash Size: 16 MB

Status:
Operational

Notes:
Display operational during testing.

---

## Board 003 - ESP32-C3 SuperMini

### Interface
- USB Serial/JTAG
- COM12

### Identification Results

Chip Type:
ESP32-C3 (QFN32)

Features:
- WiFi
- Bluetooth 5 LE
- Single Core
- 160 MHz
- Embedded Flash

Crystal:
40 MHz

MAC Address:
98:88:e0:ca:b4:64

Flash:
4 MB Embedded

Status:
Operational

Notes:
Required BOOT button to enter programming mode.

---

## Lessons Learned

1. Git Bash successfully installed and configured.
2. Python and pip verified operational.
3. esptool installed successfully.
4. ESP32 family identification completed using:
   python -m esptool --port COMx chip-id
5. Flash information successfully recovered.
6. COM port identification performed through Windows Device Manager.
7. ESP32-C3 required manual BOOT intervention.

---

## DronLibre Implications

Recovered hardware provides low-cost controller options for:

- Remote ID modules
- Telemetry nodes
- Drone diagnostics
- Ground station interfaces
- OLED display projects
- Sensor test fixtures
- Future DJI recovery tools

---

End of Log
