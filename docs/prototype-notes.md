# Prototype Build Notes

## Overview

This prototype demonstrates the core principles of the Budget Miner Project:
- Efficient off-grid mining using solar
- Modular and scalable GPU support
- Low idle power usage
- Simple, open-source platform built on Raspberry Pi

## Hardware Specs

- **2 x GPUs** (e.g. RTX 3060 or RX 6600)
- **Raspberry Pi 5 (8GB)**
- **24V battery bank (2S2P configuration)**
- **2 x 30A DC-DC buck converters (24V → 12V)**
- **Cooling system and fusing**
- **Solar input via MPPT charge controller**
- *(No ATX PSU required — system is fully DC-powered)*

## Power System

This prototype eliminates the need for an ATX power supply by using dedicated DC-DC buck converters to power each GPU directly from the 24V battery bank. This drastically reduces AC-DC conversion losses, enabling superior efficiency and modularity.

## Next Steps

- Log performance metrics
- Validate uptime on battery only
- Build GitHub Pages landing with wiring instructions
