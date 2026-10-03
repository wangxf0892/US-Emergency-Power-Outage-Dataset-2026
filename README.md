# ⚡ US Emergency Power Outage & Backup Capacity Dataset (2026 Edition)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)]()
[![Data Source](https://img.shields.io/badge/Data%20Source-NOAA%20%7C%20EIA%20%7C%20DOE-blue.svg)]()
[![Coverage](https://img.shields.io/badge/Coverage-50%20Metropolitan%20Areas-success.svg)]()

> **Interactive Web Tool & Real-Time Regional Guide:**  
> For local appliance runtime calculators, dynamic hurricane impact models, and live weather alerts, visit the official production application:  
> 👉 **[https://www.wangdadi.xyz](https://www.wangdadi.xyz)**

---

## 📌 Overview

This open-access repository catalogs historical power grid vulnerability metrics across **50 major metropolitan corridors** in the United States. Designed for disaster readiness planners, off-grid engineers, and homeowners, this dataset compiles localized weather hazards (hurricanes, freezing ice storms, wildfire-related PSPS events) and models the minimum battery storage capacity (Watt-hours) required to sustain critical household loads during extended multi-day blackouts.

Data aggregated from the **U.S. Energy Information Administration (EIA)**, **National Oceanic and Atmospheric Administration (NOAA)**, and local utility safety filings.

---

## 📊 50 Major US Metropolitan Hazard & Battery Sizing Index

| State | Metro Area | Primary Threat Category | Avg. Outage Duration | Recommended Battery Capacity | Technical Markdown Report | Production Web Tool |
| :---: | :--- | :--- | :---: | :---: | :---: | :---: |
| **FL** | **Miami** | Category 3+ Hurricanes & Flooding | 72-144h | `2000Wh+` | [📄 View Report](./reports/florida-miami-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/florida-miami) |
| **FL** | **Tampa** | Gulf Storm Surges & Lightning | 48-96h | `1500Wh-2000Wh` | [📄 View Report](./reports/florida-tampa-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/florida-tampa) |
| **FL** | **Orlando** | Inland Wind Gusts & Tree Snaps | 48-72h | `1000Wh-2000Wh` | [📄 View Report](./reports/florida-orlando-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/florida-orlando) |
| **FL** | **Jacksonville** | St. Johns River Storm Surges | 36-72h | `1500Wh+` | [📄 View Report](./reports/florida-jacksonville-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/florida-jacksonville) |
| **FL** | **Sarasota** | Barrier Island Coastal Surge | 72-120h | `2000Wh+` | [📄 View Report](./reports/florida-sarasota-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/florida-sarasota) |
| **FL** | **Fort Lauderdale** | Extreme Urban Flash Floods | 36-72h | `1000Wh-2000Wh` | [📄 View Report](./reports/florida-fort-lauderdale-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/florida-fort-lauderdale) |
| **FL** | **Tallahassee** | Tornado Clusters & Canopy Damage | 48-96h | `1500Wh+` | [📄 View Report](./reports/florida-tallahassee-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/florida-tallahassee) |
| **FL** | **Cape Coral** | Direct Gulf Hurricane Landfalls | 96-168h | `2000Wh+ (LFP)` | [📄 View Report](./reports/florida-cape-coral-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/florida-cape-coral) |
| **FL** | **Pensacola** | Panhandle High-Velocity Storms | 48-96h | `1500Wh+` | [📄 View Report](./reports/florida-pensacola-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/florida-pensacola) |
| **FL** | **Gainesville** | North Central Tree Snaps | 24-48h | `1000Wh+` | [📄 View Report](./reports/florida-gainesville-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/florida-gainesville) |
| **TX** | **Houston** | Gulf Tropical Systems & Freezes | 48-120h | `2000Wh+ (Expandable)` | [📄 View Report](./reports/texas-houston-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/texas-houston) |
| **TX** | **Dallas** | Severe Freezing Rain & Ice Load | 24-72h | `1500Wh+` | [📄 View Report](./reports/texas-dallas-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/texas-dallas) |
| **TX** | **Austin** | Winter Ice Canopy Failure & Heat | 36-96h | `1000Wh-2000Wh` | [📄 View Report](./reports/texas-austin-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/texas-austin) |
| **TX** | **San Antonio** | 100°F+ Transformer Overload | 24-48h | `2000Wh+` | [📄 View Report](./reports/texas-san-antonio-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/texas-san-antonio) |
| **TX** | **Fort Worth** | Severe Spring Tornado Outbreaks | 24-48h | `1500Wh+` | [📄 View Report](./reports/texas-fort-worth-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/texas-fort-worth) |
| **TX** | **El Paso** | Desert Winter Glaze & Windstorms | 12-36h | `1000Wh+` | [📄 View Report](./reports/texas-el-paso-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/texas-el-paso) |
| **TX** | **Corpus Christi** | Coastal Hurricane High-Wind | 48-96h | `1500Wh-2000Wh` | [📄 View Report](./reports/texas-corpus-christi-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/texas-corpus-christi) |
| **TX** | **Lubbock** | High Plains Ice Blizzards | 24-48h | `1500Wh+` | [📄 View Report](./reports/texas-lubbock-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/texas-lubbock) |
| **TX** | **Arlington** | Severe Thunderstorm Downbursts | 12-24h | `1000Wh+` | [📄 View Report](./reports/texas-arlington-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/texas-arlington) |
| **TX** | **Plano** | Suburban Overhead Line Freezes | 12-36h | `1000Wh+` | [📄 View Report](./reports/texas-plano-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/texas-plano) |
| **CA** | **Los Angeles** | Santa Ana Wind PSPS & Earthquakes | 24-48h | `1000Wh-2000Wh` | [📄 View Report](./reports/california-los-angeles-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/california-los-angeles) |
| **CA** | **San Diego** | Backcountry Fire Season Shutoffs | 24-48h | `1000Wh-1500Wh` | [📄 View Report](./reports/california-san-diego-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/california-san-diego) |
| **CA** | **Sacramento** | Atmospheric River Valley Storms | 48-96h | `1500Wh-2000Wh` | [📄 View Report](./reports/california-sacramento-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/california-sacramento) |
| **CA** | **San Francisco** | Bay Area Earthquake & Marine Line Silt | 24-48h | `1000Wh-1500Wh` | [📄 View Report](./reports/california-san-francisco-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/california-san-francisco) |
| **CA** | **San Jose** | Silicon Valley Rolling Outages & Heat | 12-24h | `1000Wh+` | [📄 View Report](./reports/california-san-jose-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/california-san-jose) |
| **CA** | **Fresno** | Central Valley 110°F Heat Failures | 24-48h | `2000Wh+` | [📄 View Report](./reports/california-fresno-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/california-fresno) |
| **CA** | **Riverside** | Inland Empire PSPS High Wind Trips | 24-48h | `1500Wh+` | [📄 View Report](./reports/california-riverside-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/california-riverside) |
| **CA** | **Bakersfield** | Dust Storm Substation Trip-Offs | 12-24h | `1000Wh+` | [📄 View Report](./reports/california-bakersfield-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/california-bakersfield) |
| **CA** | **Oakland** | East Bay Hills Fire Risk Outages | 24-48h | `1000Wh+` | [📄 View Report](./reports/california-oakland-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/california-oakland) |
| **CA** | **Santa Rosa** | Wine Country Catastrophic PSPS | 48-72h | `1500Wh-2000Wh` | [📄 View Report](./reports/california-santa-rosa-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/california-santa-rosa) |
| **LA** | **New Orleans** | Direct Major Hurricane Landfalls | 72-168h | `2000Wh+ (Solar Essential)` | [📄 View Report](./reports/louisiana-new-orleans-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/louisiana-new-orleans) |
| **LA** | **Baton Rouge** | Inland Hurricane Inundation | 48-96h | `1500Wh+` | [📄 View Report](./reports/louisiana-baton-rouge-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/louisiana-baton-rouge) |
| **GA** | **Atlanta** | Freezing Rain on Tree Canopy | 24-48h | `1000Wh-1500Wh` | [📄 View Report](./reports/georgia-atlanta-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/georgia-atlanta) |
| **GA** | **Savannah** | Lowcountry Coastal Storm Surges | 36-72h | `1500Wh+` | [📄 View Report](./reports/georgia-savannah-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/georgia-savannah) |
| **NC** | **Raleigh** | Piedmont Winter Glaze & Deluges | 36-72h | `1000Wh-2000Wh` | [📄 View Report](./reports/north-carolina-raleigh-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/north-carolina-raleigh) |
| **NC** | **Charlotte** | Severe Thunderstorm Microbursts | 24-48h | `1000Wh-1500Wh` | [📄 View Report](./reports/north-carolina-charlotte-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/north-carolina-charlotte) |
| **NC** | **Wilmington** | Direct Cape Fear Hurricane Strikes | 72-120h | `2000Wh+` | [📄 View Report](./reports/north-carolina-wilmington-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/north-carolina-wilmington) |
| **SC** | **Charleston** | King Tides & Nor'easter Storm Surges | 48-96h | `1500Wh+ (Wheeled Chassis)` | [📄 View Report](./reports/south-carolina-charleston-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/south-carolina-charleston) |
| **SC** | **Columbia** | Midlands River Basin Floods | 24-48h | `1000Wh+` | [📄 View Report](./reports/south-carolina-columbia-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/south-carolina-columbia) |
| **AL** | **Mobile** | Mobile Bay Storm Surges & Gusts | 48-96h | `1500Wh+` | [📄 View Report](./reports/alabama-mobile-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/alabama-mobile) |
| **AZ** | **Phoenix** | 115°F+ Heatwaves & Haboob Dust Trips | 12-36h | `2000Wh+ (Thermal Dissipation)` | [📄 View Report](./reports/arizona-phoenix-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/arizona-phoenix) |
| **AZ** | **Tucson** | Monsoon Microburst Lightning Strikes | 12-24h | `1000Wh+` | [📄 View Report](./reports/arizona-tucson-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/arizona-tucson) |
| **NV** | **Las Vegas** | Desert Heat Wave Substation Trips | 12-24h | `1000Wh-2000Wh` | [📄 View Report](./reports/nevada-las-vegas-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/nevada-las-vegas) |
| **NV** | **Reno** | Sierra Nevada Blizzard Outages | 24-48h | `1500Wh+` | [📄 View Report](./reports/nevada-reno-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/nevada-reno) |
| **NM** | **Albuquerque** | High-Desert Spring Wind Damaging Lines | 12-24h | `1000Wh+` | [📄 View Report](./reports/new-mexico-albuquerque-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/new-mexico-albuquerque) |
| **CO** | **Denver** | Spring Blizzards & Mountain Isolation | 12-36h | `1000Wh (Cold-Resistant)` | [📄 View Report](./reports/colorado-denver-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/colorado-denver) |
| **CO** | **Colorado Springs** | Pikes Peak Foothill Wind Freezes | 12-24h | `1000Wh+` | [📄 View Report](./reports/colorado-colorado-springs-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/colorado-colorado-springs) |
| **UT** | **Salt Lake City** | Wasatch Front Winter Inversion Ice | 12-24h | `1000Wh+` | [📄 View Report](./reports/utah-salt-lake-city-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/utah-salt-lake-city) |
| **MN** | **Minneapolis** | -20°F Polar Vortex Freezes | 24-72h | `1500Wh+ (Cold-Rated Battery)` | [📄 View Report](./reports/minnesota-minneapolis-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/minnesota-minneapolis) |
| **IL** | **Chicago** | Lake Effect Blizzards & Gale Winds | 24-48h | `1500Wh+` | [📄 View Report](./reports/illinois-chicago-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/illinois-chicago) |
| **MI** | **Detroit** | Aging Grid Winter Ice Storm Vulnerability | 48-96h | `1500Wh-2000Wh` | [📄 View Report](./reports/michigan-detroit-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/michigan-detroit) |
| **NY** | **Buffalo** | Historic Lake Effect Heavy Snow Loads | 48-120h | `2000Wh+` | [📄 View Report](./reports/new-york-buffalo-outage-backup-guide.md) | [⚡ Web Tool](https://www.wangdadi.xyz/power/new-york-buffalo) |

---

## 🧮 Appliance Load Estimation Formulas

To calculate your minimum portable power station requirement during a localized blackout:

$$\text{Required Battery Capacity (Wh)} = \frac{\sum (\text{Appliance Wattage} \times \text{Hours Needed})}{\text{Inverter Efficiency (0.85)} \times \text{Depth of Discharge (0.90)}}$$

### Example: Sustaining Household Essentials (Hurricane Landfall Scenario)
* **Energy Star Refrigerator:** 180W running ~35% duty cycle = 63W continuous ($63 \times 24\text{h} = 1,512\text{Wh}$)
* **Medical CPAP Machine (Humidifier Off):** 45W ($45 \times 8\text{h} = 360\text{Wh}$)
* **Total Daily Requirement:** $\approx 1,872\text{Wh}$  
* **Recommended System:** 2048Wh LiFePO4 base unit with minimum 400W solar panel input.

---

## 🔗 Official Project Links

* **Live Interactive Web Application:** [https://www.wangdadi.xyz](https://www.wangdadi.xyz)
* **30% Federal Clean Energy Tax Credit Calculator:** [https://www.wangdadi.xyz/calculators/tax-credit](https://www.wangdadi.xyz/calculators/tax-credit)
* **Appliance Sizing Calculators:** [https://www.wangdadi.xyz/#sizing-guide](https://www.wangdadi.xyz/#sizing-guide)
* **Editorial Standards & Mission:** [https://www.wangdadi.xyz/about](https://www.wangdadi.xyz/about)

---

## 📜 License & Citation

This public dataset is licensed under the [MIT License](LICENSE).  
If you reference this dataset in academic publications or disaster prep research, please cite:
> *PowerReady Hub Research Group (2026). "United States Regional Grid Reliability and Portable Energy Sizing Index." https://www.wangdadi.xyz*
