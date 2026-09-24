# Oxide Keys

A handheld mini-game console I built to learn embedded Rust on hardware I designed.

**MCU:** Raspberry Pi Pico W / RP2040  
**Firmware:** Rust, `no_std`, rp2040-hal  
**Hardware:** custom four-layer PCB designed in KiCad

## Why

I wanted to learn Rust somewhere the compiler was not the only thing that could go wrong. Building the hardware forced me to work with datasheets, GPIO, displays, physical controls and firmware at the same time.

## Hardware

- Raspberry Pi Pico W.
- Eight mechanical switches.
- RGB underglow for each key.
- Rotary encoder.
- SPI TFT display.
- Custom four-layer PCB.
- Custom enclosure.

The PCB has been fabricated and brought up successfully.

## Firmware

The firmware is written in embedded Rust.

Current work includes:

- input handling
- display integration
- launcher navigation
- rotary encoder input
- per-game controls
- Pong
- an early Space Invaders-style prototype

## What I learned

This project taught me much more than a microcontroller tutorial would have:

- reading the RP2040 documentation
- working with HAL/PAC APIs
- debugging hardware and firmware together
- designing a PCB around actual firmware requirements
- using `no_std` Rust on a real device

## Project page

https://ren-jop.github.io/oxide-keys/

## License

No open-source license has been selected yet.
