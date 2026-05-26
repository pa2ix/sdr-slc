# SDR-SLC

SDR-SLC is an open protocol suite for low-cost networked software-defined radio hardware.

The project separates:

- service discovery
- control plane
- I/Q stream transport

into clearly defined interoperable protocols.

The architecture is designed for:

- HAM radio experimenters
- home-built SDR hardware
- STM32 and Raspberry Pi implementations
- open interoperability
- host-side DSP processing

---

# Protocol Suite

## SDR-SLC-PS — Protocol Suite Architecture

Overall architecture, design philosophy, slice model, and reference hardware.

[Open PDF](assets/pdf/SDR-SLC-PS-1_0-v2.pdf)

---

## SDR-SLC-DISC — Service Discovery

mDNS/DNS-SD based automatic discovery.

[Open PDF](assets/pdf/SDR-SLC-DISC-1_0-v2.pdf)

---

## SDR-SLC-CP — Control Plane

JSON-over-TCP control protocol.

[Open PDF](assets/pdf/SDR-SLC-CP-1_0-v2.pdf)

---

## SDR-SLC-VITA — I/Q Stream Transport

VITA-49 constrained transport profiles for SDR I/Q streaming.

[Open PDF](assets/pdf/SDR-SLC-VITA-1_0-v2.pdf)

---

# Design Philosophy

SDR-SLC intentionally keeps radio hardware simple and moves DSP processing to the host computer.

This enables:

- lower hardware cost
- simpler firmware
- easier experimentation
- fully programmable DSP
- easier home-built SDR systems

---

# Status

Current status:

- Protocol suite: Release Candidate
- STM32 firmware: in development
- Client software: experimental
- Reference hardware: prototype stage
