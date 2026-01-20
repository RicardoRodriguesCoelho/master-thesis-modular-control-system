# Control PCBA (Master / Slave)

This folder contains the **control PCBA** used in the decentralized control system.

A single hardware design is used for both **master and slave nodes**.  
The role of each board is defined **only by the firmware**, not by hardware differences.

---

## Key Characteristics

- Modular PCBA design
- Interfaces with the **Texas Instruments LAUNCHXL-F28379D**
- Supports decentralized control architectures
- Communication via **SPI and GPIO-based signaling**
- Enables easy scalability by adding additional slave nodes

---

## Design Rationale

Using the same control PCBA for both master and slave roles simplifies:
- Manufacturing and assembly
- Validation and testing
- System scalability and maintenance

This approach aligns with the modular and reusable design philosophy of the project.
