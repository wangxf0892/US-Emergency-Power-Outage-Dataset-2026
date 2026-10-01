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
| **FL** | **Orlando** | Inland Wind Gusts & Tree Snaps | 48 – 72 Hours | **1000Wh – 2000Wh** | Refrigerator + Wi-Fi & Box Fans | [Orlando Guide](https://www.wangdadi.xyz/power/florida-orlando) |
| **FL** | **Jacksonville** | Coastal Nor'easters & Storm Surge | 36 – 72 Hours | **1500Wh+** | Kitchen Essentials + CPAP Backup | [Jacksonville Guide](https://www.wangdadi.xyz/power/florida-jacksonville) |
| **TX** | **Houston** | Gulf Hurricanes & Winter Freezes | 48 – 120 Hours | **2000Wh+ (Expandable)** | Deep Freezer + Oxygen Concentrator | [Houston Guide](https://www.wangdadi.xyz/power/texas-houston) |
| **TX** | **Dallas** | Sub-Zero Freezing Rain / Ice Load | 24 – 72 Hours | **1500Wh+** | 1500W Space Heater (Low) + Wi-Fi | [Dallas Guide](https://www.wangdadi.xyz/power/texas-dallas) |
| **TX** | **Austin** | Grid Capacity Strain & Ice Storms | 36 – 96 Hours | **1000Wh – 2000Wh** | Home Office Station + Starlink Dish | [Austin Guide](https://www.wangdadi.xyz/power/texas-austin) |
| **TX** | **San Antonio** | 100°F+ Summer Heat & Transformer Load | 24 – 48 Hours | **2000Wh+** | High-Temp Charging + Food Storage | [San Antonio Guide](https://www.wangdadi.xyz/power/texas-san-antonio) |
| **TX** | **Fort Worth** | Spring Tornado Outbreaks & Hail | 24 – 48 Hours | **1500Wh+** | Basement Sump Pump + Emergency Radio | [Fort Worth Guide](https://www.wangdadi.xyz/power/texas-fort-worth) |
| **CA** | **Los Angeles** | Santa Ana Wind PSPS & Wildfires | 24 – 48 Hours | **1000Wh – 2000Wh** | Air Purifier (HEPA) + Food Storage | [LA Guide](https://www.wangdadi.xyz/power/california-los-angeles) |
| **CA** | **San Diego** | Backcountry Wildfire Shutoffs | 24 – 48 Hours | **1000Wh – 1500Wh** | Medical Nebulizers + Home Modem | [San Diego Guide](https://www.wangdadi.xyz/power/california-san-diego) |
| **CA** | **Sacramento** | Winter Atmospheric River Floods | 48 – 96 Hours | **1500Wh – 2000Wh** | Garage Freezer + Drainage Sump | [Sacramento Guide](https://www.wangdadi.xyz/power/california-sacramento) |
| **LA** | **New Orleans** | Major Hurricane Landfalls | 72 – 168 Hours | **2000Wh+ (Solar Essential)** | Sump Pump + Refrigerator (Multi-Day) | [New Orleans Guide](https://www.wangdadi.xyz/power/louisiana-new-orleans) |
| **NC** | **Raleigh** | Hurricane Remnants & Winter Ice | 36 – 72 Hours | **1000Wh – 2000Wh** | Electric Blankets + Dehumidifier | [Raleigh Guide](https://www.wangdadi.xyz/power/north-carolina-raleigh) |
| **GA** | **Atlanta** | Heavy Freezing Rain on Tree Canopy | 24 – 48 Hours | **1000Wh – 1500Wh** | Bedroom CPAP + Family Communications | [Atlanta Guide](https://www.wangdadi.xyz/power/georgia-atlanta) |
| **AZ** | **Phoenix** | 115°F Heatwaves & Haboob Dust Outages | 12 – 36 Hours | **2000Wh+ (Thermal Dissipation)** | Evaporative Swamp Cooler + Misting Fan | [Phoenix Guide](https://www.wangdadi.xyz/power/arizona-phoenix) |
| **NV** | **Las Vegas** | Desert Heat Wave Grid Tripping | 12 – 24 Hours | **1000Wh – 2000Wh** | Condo Refrigerator + Induction Cooktop | [Las Vegas Guide](https://www.wangdadi.xyz/power/nevada-las-vegas) |
| **SC** | **Charleston** | King Tides & Tropical Storm Surges | 48 – 96 Hours | **1500Wh+ (Wheeled Chassis)** | Emergency Sump Pump + Evacuation Gear | [Charleston Guide](https://www.wangdadi.xyz/power/south-carolina-charleston) |
| **MN** | **Minneapolis** | -20°F Polar Vortex Freezes | 24 – 72 Hours | **1500Wh+ (Cold-Rated Battery)** | Furnace Circulating Blower + Heat Pads | [Minneapolis Guide](https://www.wangdadi.xyz/power/minnesota-minneapolis) |
| **CO** | **Denver** | High-Altitude Spring Blizzards | 12 – 36 Hours | **1000Wh (Cold-Resistant)** | Electric Heating Blanket + Comms | [Denver Guide](https://www.wangdadi.xyz/power/colorado-denver) |
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
