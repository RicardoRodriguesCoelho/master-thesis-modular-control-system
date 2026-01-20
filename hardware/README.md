# Hardware

## Hardware Overview

This folder contains all hardware developed for the decentralized modular control system, including:

- Control PCBA (Master / Slave nodes)
- Power electronics PCBA
- Gate driver boards

The hardware was designed with modularity, scalability, and reusability in mind, supporting multi-node cascaded power converter systems.

All designs were developed using Altium Designer.

## Structure
- `/pcb-control` – Modular control board used as master or slave depending on firmware
- `/pcb-power/main-board` – Main power electronics board
- `/pcb-power/driver-boards` – Isolated driver boards (ADuM3223 and ADuM4135)
