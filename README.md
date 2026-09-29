# ⚡ US Emergency Power Outage & Backup Capacity Dataset (2026 Edition)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)]()
[![Data Source](https://img.shields.io/badge/Data%20Source-NOAA%20%7C%20EIA%20%7C%20DOE-blue.svg)]()

> **Interactive Web Tool & Real-Time Regional Guide:**  
> For local appliance runtime calculators, dynamic hurricane impact models, and live weather alerts, visit the official web tool:  
> 👉 **[https://www.wangdadi.xyz](https://www.wangdadi.xyz)**

---

## 📌 Overview

This open-access repository catalogs historical power grid vulnerability metrics across major metropolitan areas in the United States. Designed for disaster readiness planners, off-grid engineers, and homeowners, this dataset compiles localized weather hazards (hurricanes, freezing ice storms, wildfire-related PSPS events) and models the minimum battery storage capacity (Watt-hours) required to sustain critical household loads during extended multi-day blackouts.

Data aggregated from the **U.S. Energy Information Administration (EIA)**, **National Oceanic and Atmospheric Administration (NOAA)**, and local utility safety reports.

---

## 📊 Regional Outage Vulnerability & Backup Sizing Index

Below is the benchmark index for high-risk metropolitan areas across the United States.

| State | Metro Area | Primary Threat Category | Avg. Outage Duration | Recommended Battery Capacity | Critical Appliance Profile | Regional Field Guide |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **FL** | **Miami** | Category 3+ Hurricane / Flooding | 72 – 144 Hours | **2000Wh+ (LFP)** | Refrigerator + Portable AC (8000 BTU) | [Miami Guide](https://www.wangdadi.xyz/power/florida-miami) |
| **FL** | **Tampa** | Gulf Storm Surges / Lightning | 48 – 96 Hours | **1500Wh – 2000Wh** | Sump Pump (1/3 HP) + Medical CPAP | [Tampa Guide](https://www.wangdadi.xyz/power/florida-tampa) |
| **TX** | **Houston** | Gulf Hurricanes & Winter Freezes | 48 – 120 Hours | **2000Wh+ (Expandable)** | Deep Freezer + Oxygen Concentrator | [Houston Guide](https://www.wangdadi.xyz/power/texas-houston) |
| **TX** | **Dallas** | Sub-Zero Freezing Rain / Ice Load | 24 – 72 Hours | **1500Wh+** | 1500W Space Heater (Low) + Wi-Fi | [Dallas Guide](https://www.wangdadi.xyz/power/texas-dallas) |
| **TX** | **Austin** | Grid Capacity Strain & Ice Storms | 36 – 96 Hours | **1000Wh – 2000Wh** | Home Office Station + Starlink Dish | [Austin Guide](https://www.wangdadi.xyz/power/texas-austin) |
| **CA** | **Los Angeles** | Santa Ana Wind PSPS & Wildfires | 24 – 48 Hours | **1000Wh – 2000Wh** | Air Purifier (HEPA) + Food Storage | [LA Guide](https://www.wangdadi.xyz/power/california-los-angeles) |
| **CO** | **Denver** | High-Altitude Blizzards / Camping | 12 – 36 Hours | **1000Wh (Cold-Resistant)**| Electric Heating Blanket + Comms | [Denver Guide](https://www.wangdadi.xyz/power/colorado-denver) |
| **UT** | **Moab** | Desert Heat & Off-Grid Isolation | 24 – 48 Hours | **1000Wh + 400W Solar** | 12V 45L Portable Fridge/Freezer | [Moab Guide](https://www.wangdadi.xyz/power/utah-moab) |

---

## 🧮 Appliance Load Estimation Formulas

To calculate your minimum portable power station requirement during a localized blackout:

$$\text{Required Battery Capacity (Wh)} = \frac{\sum (\text{Appliance Wattage} \times \text{Hours Needed})}{\text{Inverter Efficiency (0.85)} \times \text{Depth of Discharge (0.90)}}$$

### Example: Sustaining Household Essentials (Miami Hurricane Scenario)
* **Energy Star Refrigerator:** 180W running ~35% duty cycle = 63W continuous ($63 \times 24\text{h} = 1,512\text{Wh}$)
* **Medical CPAP Machine (Humidifier Off):** 45W ($45 \times 8\text{h} = 360\text{Wh}$)
* **Total Daily Requirement:** $\approx 1,872\text{Wh}$  
* **Recommended System:** 2048Wh LiFePO4 base unit with minimum 400W solar panel input.

---

## 🔗 Official Project Links

* **Live Interactive Web Application:** [https://www.wangdadi.xyz](https://www.wangdadi.xyz)
* **Regional Outage Calculators:** [https://www.wangdadi.xyz/#regional-guides](https://www.wangdadi.xyz/#regional-guides)
* **Editorial Standards & Mission:** [https://www.wangdadi.xyz/about](https://www.wangdadi.xyz/about)

---

## 📜 License & Citation

This public dataset is licensed under the [MIT License](LICENSE).  
If you reference this dataset in academic publications or disaster prep research, please cite:
> *PowerReady Hub Research Team (2026). "United States Regional Grid Reliability and Portable Energy Sizing Index." https://www.wangdadi.xyz*# US-Emergency-Power-Outage-Dataset-2026
Open dataset of US regional electrical grid vulnerabilities and portable solar generator sizing benchmarks.
