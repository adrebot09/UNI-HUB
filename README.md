<img width="2172" height="724" alt="UNI HUB BANNEWR" src="https://github.com/user-attachments/assets/9dfe91f2-b07d-4a87-baef-69823684e016" />
# UNI-HUB V1

<p align="center">
  <img src="docs/images/banner.png" alt="UNI-HUB V1 Banner" width="800">
</p>

<p align="center">
A compact USB 2.0 hub featuring dual upstream compatibility, four downstream ports, per-port LED indicators, and an open-source hardware design.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-V1-blue">
  <img src="https://img.shields.io/badge/Hardware-USB%202.0-success">
  <img src="https://img.shields.io/badge/Designed%20in-India-orange">
  <img src="https://img.shields.io/badge/Status-Prototype-red">
</p>

---

# Overview

UNI-HUB V1 is a custom-designed USB 2.0 hub developed from the ground up using EasyEDA. The project was created as a hardware engineering learning experience while following proper PCB design practices and preparing the board for professional SMT assembly.

Unlike many beginner projects, UNI-HUB V1 was designed with manufacturability in mind using LCSC components and JLCPCB assembly-compatible footprints.

---

# Features

- 4 USB 2.0 Downstream Ports
  - 2 × USB Type-A
  - 2 × USB Type-C

- Dual Upstream Connectivity
  - USB Type-C
  - USB Type-A
  - *(Only one upstream connector should be connected at a time.)*

- Individual LED Power Indicator for every downstream port

- USB-C CC resistor implementation following USB Type-C specifications

- Professional PCB Layout

- Designed for JLCPCB SMT Assembly

- Open Source Hardware

---

# Hardware Specifications

| Specification | Value |
|--------------|-------|
| USB Standard | USB 2.0 High-Speed |
| Hub Controller | SL2.1A |
| Upstream Ports | 1 × USB-C + 1 × USB-A |
| Downstream Ports | 2 × USB-A + 2 × USB-C |
| Power | USB Bus Powered |
| PCB Layers | 2 Layer |
| Indicator LEDs | 4 |
| CAD Software | EasyEDA Pro |

---

# Project Structure

```
UNI-HUB/
│
├── hardware/
│   ├── schematic/
│   ├── pcb/
│   ├── gerber/
│   ├── bom/
│   └── cpl/
│
├── docs/
│   ├── journal/
│   ├── renders/
│   ├── images/
│   └── datasheets/
│
├── LICENSE
├── README.md
└── CHANGELOG.md
```

---

# Development Process

The project followed a structured engineering workflow:

- Research
- Component Selection
- Schematic Design
- Component Verification
- PCB Routing
- Design Rule Verification
- Manufacturing Preparation

Every major milestone was documented throughout development.

---

# PCB Highlights

- Differential pair routing
- USB-C CC implementation
- Decoupling capacitor placement
- Individual power indicator LEDs
- Compact board layout
- Manufacturing-ready footprints

---

# Manufacturing

Designed for:

- EasyEDA Pro
- LCSC Components
- JLCPCB SMT Assembly

The repository includes all production files required for fabrication.

---

# Software Used

- EasyEDA Pro
- Fusion 360 *(planned enclosure design)*
- Git & GitHub

---

# Repository Contents

- Schematics
- PCB Design
- Gerber Files
- Bill of Materials (BOM)
- Pick & Place (CPL)
- Development Journal
- Documentation

---

# Future Improvements (V2)

- USB 3.x Support
- Power Protection Improvements
- ESD Protection
- Automatic Upstream Detection
- Custom Enclosure
- Activity LEDs
- Improved Silkscreen Artwork

---

# Designed & Developed By

**@AdreBot**

Designed and Developed in India

2026

---

# License

This project is released as open-source hardware.

Choose your preferred license before public release.

Recommended:

MIT License

or

CERN Open Hardware License v2

---

# Acknowledgements

Special thanks to:

- EasyEDA
- LCSC
- JLCPCB
- Hack Club Macondo

for providing the tools and ecosystem that made this project possible.

---

# Project Status

Current Version

**UNI-HUB V1**

Status:

**PCB Design Complete**

Ready for prototype manufacturing.

---

## ⭐ If you found this project interesting, consider starring the repository.
