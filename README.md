# STM32 Synth

Handheld digital synth
Hardware in Altium, firmware in embedded C.

## Planned Features

- Capacitive touch for notes + octave
- Pots for pitch, volume, and envelope
- 12-bit DAC audio out to a speaker amp
- OLED display with encoder menu

## Hardware

- MCU: STM32F446RET6
- Display: TBD
- Audio: DAC, RC filter, PAM8302 amp
- Power: USB-C 5V to charge LiPo, 3.3V regulator

## Repo Structure

- `hardware/` Altium files
- `firmware/` STM32CubeIDE project

## Status

In progress. Working on the schematic.
