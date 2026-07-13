# Hardware

This directory contains the hardware design files for the **Temp Reader** project, developed using **KiCad 9.0**.

## Contents

- **TempReader.kicad_pro** – KiCad project file
- **TempReader.kicad_sch** – Top-level schematic
- **Transmitter.kicad_sch** – Transmitter schematic
- **Receiver.kicad_sch** – Receiver schematic
- **TempReader.kicad_pcb** – PCB layout (currently under development)

## Hardware Overview

The hardware consists of two ESP32-based boards:

### Transmitter
- ESP32-WROOM-32
- Bosch BME280 environmental sensor
- nRF24L01 wireless transceiver
- AP62150WU buck converter for 3.3 V power supply

### Receiver
- ESP32-WROOM-32
- nRF24L01 wireless transceiver
- Display interface for real-time sensor data visualization

## Current Status

- ✅ Electronic schematics completed
- 🚧 PCB layout in progress
- ⏳ Firmware development planned
- ⏳ Hardware testing pending

## Software

The firmware is not included in this directory and will be available in the `/Firmware` folder once development begins.
