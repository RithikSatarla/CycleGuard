# CycleGuard — Bicycle Safety System

A bicycle-mounted electronic safety system that detects vehicles approaching from behind, estimates closing speed and time-to-collision, and alerts the rider through vibration and adaptive lighting.

## System Architecture

### Rear Unit (under seat)
- ESP32-S3 microcontroller
- Rear-facing radar module
- IMU (6-axis accelerometer + gyroscope)
- Ambient-light sensor
- High-brightness red LEDs
- microSD card for logging
- Rechargeable battery

### Handlebar Unit (near rider's hands)
- ESP32 board
- Vibration motor
- Status LEDs
- Small battery

## Target Specifications

| Metric | Target |
|--------|--------|
| Vehicle detection range | ≥10 m |
| Warning latency | <250 ms |
| Operating time | ≥5 hours |
| System mass | <500 g |

## Project Status

**Phase 1 Progress:**
- ✓ Arduino IDE installed
- ✓ ESP32-S3 board setup
- ✓ LED blink test working
- ✓ Button input test working
- ✓ Serial sensor data test working
- Next: Bluetooth test, Phase 2 (adaptive light)
