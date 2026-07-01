# CycleGuard Engineering Log

A running record of progress, tests, and decisions.

---

## Week 1 — Phase 1: Foundation & ESP32 Setup

### Day 1-2: Initial Setup
- Installed Arduino IDE
- Added Espressif ESP32 board support
- Selected ESP32-S3 Dev Board
- Connected via COM5

### Day 3: LED Blink Test ✓
- Uploaded Blink example
- LED on board blinks on/off repeatedly
- Confirmed upload pipeline works

### Day 4: Button Input Test ✓
- Used BOOT button (GPIO 0)
- Read button state via digitalRead()
- Printed "Button PRESSED" / "Button not pressed" to Serial Monitor
- Serial monitor set to 115200 baud

### Day 5: Serial Sensor Data Test ✓
- Printed simulated sensor readings (temperature, light, voltage)
- CSV format output to Serial Monitor
- Data refreshes every 500ms

### Next Steps
- [ ] Bluetooth test (Test 5)
- [ ] Order microSD module for SD card test
- [ ] Phase 2: Build adaptive rear light
  - Wire LED + MOSFET
  - Add ambient light sensor
  - Program brightness control

---

## Notes
- USB cable must support data transfer, not just charging
- Serial monitor needs correct baud rate (115200) to connect
- Always test components individually before combining
