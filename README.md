# Custom Workstation Engineering & Optimization

**Objective:** To architect, source, and build a high-performance computing system from component-level parts, ensuring hardware and firmware compatibility, optimizing thermal and power performance, and establishing a stable platform for cybersecurity software testing and analysis.

## 🛠️ Technical Implementation

### 1. System Architecture & Component Selection
- Researched and selected complementary components based on performance benchmarks, power requirements, and compatibility constraints.
- **Key Components:** 
  - **CPU:** AMD Ryzen 7 7700X
  - **GPU:** AMD Radeon RX 6700 XT
  - **RAM:** 32GB (2x16) DDR5
  - **Storage:** 1TB NVMe SSD (Primary), 500GB SSD (Secondary)
  - **Motherboard:** MSI PRO B650-P WIFI
  - **PSU:** Corsair RMe Series RM1000e 80 PLUS Gold
  - **Cooling:** Lian Li Galahad AIO Cooler
  - **Case:** Lian Li PC Case

### 2. Assembly & Physical Deployment
- Assembled the system employing best practices in electrostatic discharge (ESD) safety.
- Implemented advanced cable management to ensure optimal airflow and reduce dust accumulation.
- Mounted the Lian Li Galahad AIO cooler for efficient thermal dissipation of the Ryzen 7 7700X.

### 3. Firmware & Low-Level Configuration
- Flashed the MSI motherboard to the latest UEFI/BIOS firmware version for security patches and hardware support.
- Configured UEFI settings: enabled EXPO for DDR5 rated speeds, configured fan curves, and enabled hardware virtualization support (SVMM/VT-d) for running virtualized sandboxes and malware analysis labs.

### 4. Software Stack & Baseline Configuration
- Performed a clean installation of **Windows 10 Pro**.
- Installed and updated all hardware-specific drivers from manufacturer sources.
- Installed a baseline security stack and configured host firewall rules.

## 📊 Performance & Validation
- **Stress Testing:** Validated thermal performance and stability using Cinebench R23 and 3DMark; CPU temperatures maintained at <80°C under full load thanks to the AIO cooler.
- **Issue Resolution:** Diagnosed and resolved a `VGA_POST` error on first boot by reseating the GPU and ensuring power connector integrity.

## 🎯 Skills Demonstrated
- `Hardware Troubleshooting` | `System Architecture` | `Firmware Management`
- `Performance Optimization` | `Technical Documentation`

## 🔗 Value to Cybersecurity
This project demonstrates a foundational understanding of the endpoint hardware that cybersecurity tools operate on. The troubleshooting process mirrors SOC alert triage: isolating variables, testing hypotheses, and identifying root cause. Configuring hardware virtualization support directly enables safer malware analysis environments.

> *This custom-built workstation serves as my primary lab environment for conducting security research, vulnerability testing, and running virtualized networks.*
