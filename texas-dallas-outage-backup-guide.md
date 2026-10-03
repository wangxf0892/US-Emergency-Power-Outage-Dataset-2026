# ⚡ Dallas, TX Emergency Power Outage & Solar Generator Sizing Guide (2026)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Dataset](https://img.shields.io/badge/Dataset-US--Grid--Reliability--2026-blue.svg)](../README.md)
[![Live Interactive Tool](https://img.shields.io/badge/Web%20Tool-PowerReady%20Hub-orange.svg)](https://www.wangdadi.xyz/power/texas-dallas)

> **Regional Emergency Directive:**  
> This engineering datasheet provides baseline battery storage calculations for residents in **Dallas, Texas** subject to **Severe Freezing Rain & Ice Load**.  
> For real-time appliance runtime simulations and live storm updates, visit the production web app:  
> 👉 **[Interactive Dallas Power Outage Calculator (https://www.wangdadi.xyz/power/texas-dallas)](https://www.wangdadi.xyz/power/texas-dallas)**

---

## 📌 Metropolitan Risk Profile: Dallas, TX

* **Primary Grid Hazard:** Severe Freezing Rain & Ice Load
* **Regional Utility Provider:** Oncor Electric Delivery
* **Historical Multi-Day Outage Window:** 24-72h
* **Recommended Household Battery Baseline:** `1500Wh+`
* **Statutory 30% IRS Section 25D Credit Eligibility:** All standalone systems $\ge 3000\text{Wh}$ qualify on IRS Form 5695 ([Calculate 30% Tax Refund](https://www.wangdadi.xyz/calculators/tax-credit)).

---

## 🧮 Appliance Load Sizing Benchmarks for Dallas

During extended grid collapses in Dallas, sustaining food refrigeration and medical equipment is critical:

| Household Appliance | Continuous Draw | Starting Inrush Surge | Minimum Station Sizing | Expected Runtime | Technical Guide |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Kitchen Refrigerator / Freezer** | 150W – 250W | 800W – 1200W | 1500Wh – 2000Wh (LFP) | 12 – 16 Hours (Cycles) | [Fridge Runtime Guide](https://www.wangdadi.xyz/appliances/run-refrigerator-on-solar-generator) |
| **Medical CPAP / BiPAP** | 35W – 60W | None (DC Steady) | 500Wh – 1000Wh | 2 – 4 Full Nights | [CPAP Sizing Guide](https://www.wangdadi.xyz/appliances/run-cpap-on-solar-generator) |
| **Basement Sump Pump (1/3 HP)** | 700W – 900W | 2000W – 2500W | 2000Wh+ (High Surge) | 40 – 80 Pump Cycles | [Sump Pump Guide](https://www.wangdadi.xyz/appliances/run-sump-pump-on-solar-generator) |
| **Home Wi-Fi + Starlink + Laptops**| 25W – 75W | Minimal | 500Wh – 768Wh | 18 – 35 Hours | [Comms Backup Guide](https://www.wangdadi.xyz/appliances/run-wifi-router-and-starlink-on-solar-generator) |

### Battery Runtime Formula:
$$\text{Continuous Hours} = \frac{\text{Battery Capacity (Wh)} \times 0.85 \text{ (Inverter Efficiency)} \times 0.90 \text{ (DoD)}}{\text{Continuous Load Wattage (W)}}$$

---

## 🔗 Official Verification & Resources

* **Live Interactive Web Application:** [https://www.wangdadi.xyz](https://www.wangdadi.xyz)
* **30% Federal Clean Energy Tax Credit Calculator:** [https://www.wangdadi.xyz/calculators/tax-credit](https://www.wangdadi.xyz/calculators/tax-credit)
* **Official Editorial Standards & Safety Benchmarks:** [https://www.wangdadi.xyz/about](https://www.wangdadi.xyz/about)
* **Master National Outage Index:** [Parent Repository Overview](../README.md)

---
*Report maintained by PowerReady Hub Research Group · Data verified against NOAA & EIA statutory reliability standards.*
