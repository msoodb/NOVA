# NOVA
NOVA — Network Overlay for Verified Access — is a secure, modular ecosystem for remote control, encrypted communication, and autonomous robotics.

This repository serves as the central container for the NOVA ecosystem, linking together its key components:
NOVA Architecture Overview

NOVA is designed to transform standard communication devices and robotic systems into secure, extensible, and coordinated platforms. It enables modular radio communication, controller interfacing, and autonomous operation with an emphasis on isolation and encryption.
Linked Modules
Belfhym

https://github.com/msoodb/belfhym
An embedded control framework for RC cars and autonomous ground robots. Built on STM32 with FreeRTOS, Belfhym handles motor control, sensor input, failsafe mechanisms, and actuator logic.
S17

https://github.com/msoodb/S17
A secure radio communication module designed to isolate and protect transmissions. S17 handles the lower-level protocol logic and supports plug-and-play encryption layers between devices.
Hermes

https://github.com/msoodb/hermes
A modern remote controller framework inspired by the messenger god Hermes. This module enables real-time command dispatching and supports radio interfaces like NRF24L01 for seamless integration with robotic units.
Why NOVA?

NOVA offers a security-first architecture, enabling encrypted communication via isolated modules. Its modular design allows each subproject to operate independently while integrating seamlessly. NOVA is open, scalable, and acts as a drop-in hardware-agnostic gateway to secure existing systems.
Getting Started

This repository contains no source code directly, but links and documents the full ecosystem. To begin using or contributing to NOVA:

- Start with S17 to understand the communication protocol.
- Explore Hermes to see how the remote controller interacts.
- Deploy on a robot using Belfhym.

Repository Structure

```text
nova/
├── README.md — This file
├── docs/ — (Optional) Architectural diagrams, specs, protocols
└── links.md — List of all related NOVA modules and tools
```

Status

NOVA is under active development. Contributions, feedback, and test deployments are welcome.
License

All components maintain their individual licenses. This container repository itself is licensed under MIT.
Contact

Created by @msoodb
