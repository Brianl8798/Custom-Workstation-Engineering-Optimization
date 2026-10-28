# Custom Workstation Engineering & Optimization : A Home Lab Built from Parts

<p align="center">
  A high-performance workstation architected, built and tuned from component-level parts to serve as a stable platform for cybersecurity labs.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CPU-Ryzen_7_7700X-ED1C24?logo=amd&logoColor=white" alt="Ryzen 7 7700X">
  <img src="https://img.shields.io/badge/GPU-RX_6700_XT-ED1C24?logo=amd&logoColor=white" alt="RX 6700 XT">
  <img src="https://img.shields.io/badge/RAM-32GB_DDR5-555555" alt="32GB DDR5">
  <img src="https://img.shields.io/badge/OS-Windows_10_Pro-0078D6?logo=windows&logoColor=white" alt="Windows 10 Pro">
</p>

> [!TIP]
> **Hardware at a glance** — jump to [Component selection](#1-system-architecture--component-selection).
>
> - 🧩 Built from **component-level parts** with full compatibility checks
> - ❄️ CPU held **under 80°C** at full load
> - 🛠️ Diagnosed and fixed a **`VGA_POST`** boot error
> - 🧪 **Hardware virtualization** enabled for malware analysis labs

## Table of Contents

- [Introduction](#introduction)
- [Technical implementation](#technical-implementation)
- [Performance & validation](#performance--validation)
- [Skills demonstrated](#skills-demonstrated)
- [Value to cybersecurity](#value-to-cybersecurity)
- [Credits](#credits)

## Introduction

The goal was to **architect, source and build** a high-performance system from component-level parts: ensuring hardware and firmware compatibility, optimizing thermal and power performance, and creating a stable platform for **cybersecurity software testing and analysis**.

## Technical implementation

### 1. System architecture & component selection

Components were chosen based on performance benchmarks, power requirements and compatibility constraints.

| Component | Part |
| --- | --- |
| CPU | AMD Ryzen 7 7700X |
| GPU | AMD Radeon RX 6700 XT |
| RAM | 32GB (2x16) DDR5 |
| Storage | 1TB NVMe SSD (primary), 500GB SSD (secondary) |
| Motherboard | MSI PRO B650-P WIFI |
| PSU | Corsair RMe Series RM1000e 80 PLUS Gold |
| Cooling | Lian Li Galahad AIO Cooler |
| Case | Lian Li PC Case |

### 2. Assembly & physical deployment

- Assembled following **electrostatic discharge (ESD)** safety best practices
- Cable management for **optimal airflow** and less dust buildup
- Mounted the Lian Li Galahad AIO for efficient cooling of the Ryzen 7 7700X

### 3. Firmware & low-level configuration

- Flashed the MSI motherboard to the **latest UEFI/BIOS** for security patches and hardware support
- Configured UEFI settings:
  - **EXPO** enabled for rated DDR5 speeds
  - Custom **fan curves**
  - **Hardware virtualization (SVM)** enabled for virtualized sandboxes and malware analysis labs

### 4. Software stack & baseline configuration

- Clean installation of **Windows 10 Pro**
- Hardware drivers installed and updated from manufacturer sources
- Baseline security stack installed and **host firewall rules** configured

## Performance & validation

| Test | Result |
| --- | --- |
| Stress testing | Validated with **Cinebench R23** and **3DMark** |
| Thermals | CPU **under 80°C** at full load with the AIO cooler |
| Issue resolution | Fixed a `VGA_POST` error on first boot by reseating the GPU and checking the power connectors |

## Skills demonstrated

`Hardware Troubleshooting` · `System Architecture` · `Firmware Management` · `Performance Optimization` · `Technical Documentation`

## Value to cybersecurity

This project shows a foundational understanding of the **endpoint hardware** that security tools run on. The troubleshooting process mirrors SOC alert triage: isolate variables, test hypotheses, and identify the root cause. Enabling hardware virtualization directly supports **safer malware analysis environments**.

> *This custom-built workstation is my primary lab environment for security research, vulnerability testing and running virtualized networks.*

## Credits

- Brian Lam — [GitHub](https://github.com/Brianl8798) · [LinkedIn](https://www.linkedin.com/in/brian-lam-282176172/)
