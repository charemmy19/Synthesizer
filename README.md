STM32 Synth

A handheld digital synthesizer built on a custom PCB around the STM32F446ZET6. Hardware designed in Altium, firmware written in embedded C.

Planned Features:
Playable keys with waveform select (square, saw, triangle, sine)
Pots for pitch, volume, and envelope control
Audio output through the onboard 12-bit DAC to a speaker amp
OLED display with rotary encoder menu
MIDI input

Hardware:
MCU: STM32F446ZET6 (Cortex-M4F, 180 MHz)
Display: SSD1306 OLED (I2C)
Audio: DAC output, RC filter, PAM8302 amp
Power: USB-C 5V input, 3.3V regulator
