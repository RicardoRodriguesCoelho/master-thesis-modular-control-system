# Control PCBA (Master / Slave)

Modular control PCBA designed to operate either as a master or slave controller,
depending exclusively on the flashed firmware.

## Description
The same hardware platform is used across the system:
- One board operates as the master controller
- Additional boards operate as slave controllers

The role is defined by the firmware version, enabling a scalable system architecture
without hardware changes.

## Hardware
- Compatible with TI LaunchXL-F28379D
- Designed for modular and decentralized control
- Interfaces with the power stage and communication network
