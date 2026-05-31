# ESP32 Inventory Log 001

Date: 2026-05-31

## ESP32-S3

Connected successfully on COM11.

Chip:
ESP32-S3 (QFN56)

Features:
- WiFi
- Bluetooth 5 LE
- Dual Core + LP Core
- 240 MHz
- Embedded PSRAM 8 MB

Flash:
- 16 MB detected

Status:
Operational.

---

## ESP32-C3

Connected successfully on COM12.

Chip:
ESP32-C3 (QFN32)

Features:
- WiFi
- Bluetooth 5 LE
- Single Core
- 160 MHz

Flash:
- 4 MB embedded

Status:
Operational.

---

## ESP32-D0WD-V3

Connected successfully on COM10.

Features:
- WiFi
- Bluetooth
- Dual Core
- 240 MHz

Status:
Operational.

---

## Notes

Successfully validated communication using esptool.

Commands verified:

python -m esptool --port COMxx chip-id

python -m esptool --port COMxx flash-id

ESP32-C3 required BOOT button held during connection.

Project:
DronLibre Hardware Discovery
