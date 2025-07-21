# unwn Firmware Releases

Public firmware distribution for unwn devices.

## Eisei Firmware

This repository contains firmware releases for the Eisei spectral audio processor:

- **Daisy (STM32H750)**: Real-time audio processing firmware
- **ESP32-S3**: UI controller firmware

## Usage

### Automated Updates via DRO Tools

The easiest way to update your Eisei firmware is through the DRO development tools:

1. Open the [DRO tools](https://github.com/unwndevices/DRO)
2. Navigate to ESP32 or Daisy flasher
3. Select firmware version from the dropdown
4. View changelog and flash

### Manual Download

Firmware binaries are available in the `firmware/eisei/` directory:

- Latest Daisy firmware: [firmware/eisei/daisy/latest.bin](firmware/eisei/daisy/latest.bin)
- Latest ESP32 firmware: [firmware/eisei/esp32/latest.bin](firmware/eisei/esp32/latest.bin)

## Release Information

Current release information is available in [releases.json](releases.json).

## Hardware

The Eisei features dual MCU architecture:
- **STM32H750 (Daisy)**: Real-time spectral processing
- **ESP32-S3**: UI management and display control

For more information about the hardware, visit the main project repository (private).