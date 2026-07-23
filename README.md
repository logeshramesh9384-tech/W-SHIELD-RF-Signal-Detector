# W-SHIELD: Wireless Signal Harvesting and Integrated Energy for Local Detection

A dual-purpose system that detects unauthorized wireless devices (mobile phones, Bluetooth, hidden cameras/microphones) in secure environments **while simultaneously harvesting ambient RF energy** to power low-energy devices like floodlights and sensors.

> **Institution:** Velammal Engineering College (Autonomous), Chennai
> **Department:** Electronics and Communication Engineering
> **Team:** Sivaram Varma M · Logeshkumar R · Ravikumar M
> **Supervisor:** Dr. J.S. Leena Jasmine
> **Academic Year:** Even Sem 2024–25

📄 **[Full Project Report (PDF)](./W-SHIELD_Report.pdf)**

---

## 📌 Table of Contents

- [Abstract](#abstract)
- [Objective](#objective)
- [Literature Survey](#literature-survey)
- [Block Diagram](#block-diagram)
- [Hardware Details](#hardware-details)
- [Description](#description)
- [Circuit Diagram](#circuit-diagram)
- [Original Connection](#original-connection)
- [Applications](#applications)
- [Graphs](#graphs)
- [Benefits](#benefits)
- [Outcome](#outcome-of-the-project)
- [References](#references)

---

## Abstract

This project introduces a wireless signal detection system designed for secure environments such as examination halls or high-security areas, capable of detecting active mobile devices (cell phones, Bluetooth, etc.) emitting signals in the **0.9 GHz to 3 GHz** range — even through barriers like clothing or thin materials — with real-time LED alerts.

It also monitors local radiation levels to ensure exposure stays within safe health limits, and detects other wireless transmissions such as hidden cameras or microphones for enhanced security.

A key feature is **RF energy harvesting**: excess RF energy from crowded spaces (e.g., railway stations) is captured and converted into usable power for low-energy devices like floodlights — promoting sustainability and reducing dependence on external power.

A graphical interface visualizes energy harvesting efficiency, radiation sources, and conversion data, helping users optimize resource usage. The system is cost-effective, scalable, and easy to implement across various environments.

## Objective

- Detect active mobile devices and wireless transmissions in the 0.9 GHz–3 GHz range, even through barriers, with LED alerts.
- Monitor local radiation levels to keep exposure within safe limits.
- Detect hidden surveillance devices (cameras, microphones) for improved security.
- Harvest excess RF energy in high-traffic areas (railway stations, airports) to power low-energy devices sustainably.
- Provide a graphical interface for visualizing energy harvesting, radiation sources, and conversion efficiency.
- Remain cost-effective, easy to deploy, and adaptable — from small rooms to large public spaces.

## Literature Survey

| # | Focus Area | Summary |
|---|-----------|---------|
| 1 | Wireless Signal Detection for Security | RF spectrum analysis and frequency scanning detect unauthorized transmitters, even through barriers like clothing/walls. |
| 2 | Radiation Monitoring | Real-time monitoring keeps RF exposure within safe limits, protecting health. |
| 3 | Energy Harvesting | Captures excess RF energy (mobile, Wi-Fi, Bluetooth) to power low-energy devices; dense environments (airports, stations) offer strong harvesting potential. |
| 4 | Security + Energy Integration | Combined systems use harvested RF energy to power sensors/floodlights while detecting unauthorized transmissions. |
| 5 | Graphical Data Visualization | Interfaces help visualize harvesting efficiency and radiation levels for real-time decisions. |
| 6 | Cost-Effective & Scalable Design | Low-cost components enable deployment from small rooms to large public spaces. |
| 7 | Challenges & Future Research | Improving harvesting efficiency and detection accuracy in weak-signal environments; ongoing antenna/sensor research. |

## Block Diagram

![Block Diagram](./images/block-diagram.png)

## Hardware Details

- **Antenna** – Receives RF signals for detection and energy harvesting
- **Transistors / ICs** – Amplification and signal processing
- **Capacitors** – Energy storage, filtering, signal stabilization
- **Resistors** – Voltage/current regulation
- **Diodes** – Rectification (AC → DC power conversion)
- **Variable Resistor / Potentiometer** – Tuning and adjustment of circuit parameters
- **Wires & Breadboard** – Prototyping and component connections

## Description

The system detects active mobile devices and wireless signals (0.9–3 GHz), even hidden under clothing, and alerts users via LED. It continuously monitors local radiation levels to ensure they stay within global health safety standards, and can also detect hidden surveillance devices like microphones or cameras.

Its standout feature is **RF energy harvesting** — in high-density environments (railway stations, airports, malls), it captures and converts excess RF energy from active devices into usable electrical power, which can drive floodlights, sensors, or other small equipment. This reduces reliance on traditional power sources.

A graphical interface displays harvested energy, conversion efficiency, and radiation sources for easy monitoring. The modular, low-cost design scales from small rooms to large public spaces with minimal installation effort.

## Circuit Diagram

![Circuit Diagram](./images/circuit-diagram.png)

## Original Connection

![Original Hardware Connection](./images/original-connection.png)

## Applications

1. **High-Security Areas** (Government, Military, Corporate) — detects hidden surveillance devices to prevent espionage or data leaks.
2. **Examination Halls & Educational Institutions** — flags unauthorized mobile device use to prevent cheating.
3. **Public Spaces & Transportation Hubs** (Railway Stations, Airports) — detects illegal devices while harvesting RF energy to power lights, cameras, sensors.
4. **Healthcare Facilities** — prevents wireless interference with sensitive medical equipment like pacemakers/imaging systems.
5. **Workplaces (Sensitive Data Protection)** — detects devices used to steal/transmit confidential data.
6. **Smart Cities & Public Infrastructure** — powers street lights, traffic signals, and surveillance cameras via harvested RF energy.
7. **Surveillance & Anti-Espionage** — protects conference rooms and executive offices from hidden recording devices.
8. **Environmental Monitoring** — tracks EM radiation in industrial plants, labs, and telecom towers.
9. **Energy Efficiency Projects** — powers floodlights/sensors in commercial and off-grid spaces via ambient RF harvesting.
10. **Smart Homes & Offices** — monitors wireless device usage while reducing energy costs.
11. **Agricultural & Remote Areas** — powers remote sensors, irrigation, and weather monitoring devices.
12. **Smart Grids & Energy Management** — detects unauthorized devices that could disrupt grid systems.
13. **Consumer Electronics & IoT Networks** — detects rogue devices on IoT networks while harvesting energy for sensors.

## Graphs

![Energy Harvesting Graph](./images/graph-1.png)
![Radiation Monitoring Graph](./images/graph-2.png)

## Benefits

- Detects unauthorized wireless devices — preventing cheating, data theft, and surveillance
- Monitors RF radiation to keep exposure within safe limits
- Captures excess RF energy to power floodlights/sensors
- Affordable, low installation and maintenance cost
- Scalable — from small rooms to large public spaces
- Reduces reliance on traditional power sources
- Real-time alerts and data visualization
- Simple setup, no specialized expertise required
- Supports sustainable energy use
- Versatile across exams, security, and public infrastructure use cases

## Outcome of the Project

The project successfully delivers a dual-purpose wireless signal detection and RF energy harvesting system, combining **security and sustainability**. It detects unauthorized mobile devices, Bluetooth signals, and hidden surveillance equipment in real time — critical for government buildings, exam halls, and corporate offices.

Its energy harvesting function captures ambient RF energy to power floodlights, sensors, and cameras, making it cost-effective and environmentally friendly. Radiation monitoring ensures RF exposure stays within safe limits, particularly valuable in hospitals and research labs. The modular, scalable design allows deployment across a wide range of environments — from classrooms to smart cities — offering a comprehensive, sustainable security and energy solution.

## References

1. Zhou, X., & Yang, Y. (2022). *A Comprehensive Survey on RF Energy Harvesting: Applications and Challenges.* Sensors, 22(8), 2990.
2. Zhang, L., & Wang, Z. (2017). *RF Power Harvesting: A Review on Designing Methodologies and Applications.* Mobile Networks and Applications, 22(5), 1005–1020.
3. Chen, M., & Zhang, Y. (2022). *Secure Communication for RF Energy Harvesting NOMA Relaying Networks.* Wireless Personal Communications, 124(1), 345–360.
4. Lu, X., & Zhang, L. (2014). *Wireless Networks with RF Energy Harvesting: A Contemporary Survey.* IEEE Transactions on Wireless Communications, 13(8), 4607–4621.
5. Gupta, V., Kalamkar, S. S., & Banerjee, A. (2017). *On Secure Communication using RF Energy Harvesting Two-Way Untrusted Relay.* arXiv:1708.07989.
6. Nguyen, T. N., et al. (2022). *Security-Reliability Trade-Off Analysis for SWIPT- and AF-Based IoT Networks with Friendly Jammers.* arXiv:2206.04428.
7. YouTube — Wireless Signal Detection and AMALDA FOX Logs.

---

⭐ If you found this project interesting, consider giving it a star!
