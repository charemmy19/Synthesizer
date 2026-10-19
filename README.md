# STM32 Synth

Handheld digital synth on a custom STM32 PCB.
Hardware in Altium, firmware in embedded C.

## Planned Features

- Keys with waveform select
- Pots for pitch, volume, and envelope
- 12-bit DAC audio out to a speaker amp
- OLED display with encoder menu
- MIDI input

## Hardware

- MCU: STM32F446RET6
- Display: SSD1306 OLED (I2C)
- Audio: DAC, RC filter, PAM8302 amp
- Power: USB-C 5V, 3.3V regulator

## Repo Structure

- `hardware/` Altium files
- `firmware/` STM32CubeIDE project

## Status

In progress. Working on the schematic.
