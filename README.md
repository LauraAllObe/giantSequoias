# 🌡️ Giant Sequoias | Urban Futures Hackathon (AMNH)

## Co-Creating Climate Resilience in NYC  
**American Museum of Natural History | LEAP Hackathon | January 2026**

**Our Team**: Abby Shaum | Arya Roi | Kevin Chan | Laura Lovelace | Zoe Tseng

---

## Project Overview

This project was developed during the **Urban Futures: Co‑Creating Climate Resilience in NYC Hackathon**, hosted by the **American Museum of Natural History (AMNH)** in partnership with **LEAP**.

Our team, **Giant Sequoias**, focused on addressing **urban heat vulnerability in Soundview, Bronx**, a historically underserved neighborhood facing disproportionate heat exposure due to limited green space, high impervious surface area, and vulnerable populations.

We explored how **data-driven climate modeling and urban design interventions** could help mitigate future heat risk using publicly available datasets and climate projections.

---

## Problem Statement

> *How can underutilized land in Soundview, Bronx be leveraged to reduce heat vulnerability through green infrastructure interventions?*

Key challenges:
- High surface temperatures and heat vulnerability
- Aging population and environmental justice concerns
- Limited green space and tree canopy
- Climate projections showing worsening conditions

---

## Data Sources

We integrated data from multiple open and research-backed sources:

- **Youth Ministries for Peace & Justice (YMPJ)**  
  → 49 identified redevelopment sites in Soundview  
- **CESM2 SSP2‑4.5 Climate Model**  
  → Regional temperature projections (2025–2035)  
- **Google Earth Engine (Landsat 8)**  
  → High-resolution surface temperature data  
- **NYC Zoning & Environmental Justice Data**
- **Public Health & Climate Literature** (20+ sources)

---

## Methodology

### 1. Data Preparation
- Compiled demographic, zoning, and site data for **49 redevelopment locations**
- Converted site addresses to latitude/longitude coordinates
- Aggregated climate and environmental attributes into analysis-ready datasets

### 2. Temperature Modeling
- Extracted **surface temperature data (2025)** from Landsat (30m resolution)
- Applied **CESM2 climate deltas** to project:
  - 2025 → 2030
  - 2025 → 2035
- Converted surface temperature to air temperature using published correction factors

### 3. Intervention Modeling
We evaluated **six heat-mitigation strategies**, each backed by academic literature:

- Tree canopy expansion  
- Green roofs  
- Reflective (cool) roofs  
- Green walls  
- Increased pervious surfaces  
- Community green spaces  

Each intervention was assigned an average cooling value based on:
- Peer‑reviewed studies
- NYC planning guidelines
- Environmental research benchmarks

### 4. Impact Analysis
For each site, we:
- Applied intervention cooling factors
- Calculated projected temperature reductions for 2030 & 2035
- Compared outcomes across intervention types

---

## Visualization & Results

- Created **interactive StoryMaps** using ArcGIS
- Built comparative charts showing:
  - No‑intervention vs intervention scenarios
  - Temperature trends over time
- Visualized:
  - Heat intensity
  - Site location
  - Zoning
  - Percentage of elderly population

These tools allow policymakers and community organizers to quickly identify **high‑impact intervention areas**.

---

## Key Findings

- Green infrastructure can reduce localized temperatures by **up to ~1–2°C**
- Tree canopy and green roofs showed the highest cooling potential
- Targeting high‑risk sites yields significantly better outcomes than uniform interventions
- Small, data-driven changes can meaningfully improve climate resilience

---

## Team: Giant Sequoias

- **Abby Shaum**: Project lead, research, climate modeling
- **Arya Roi**: Team lead, StoryMaps, visualization
- **Kevin Chan**: Stakeholder communication, ml, climate modeling
- **Laura Lovelace**: Climate modeling, data integration & analysis, research
- **Zoe Tseng**: Data collection, StoryMaps, visualization

---

## Tools & Technologies

- Python, JupyterHub (LEAP Pangeo)
- Google Earth Engine
- CESM2 Climate Models
- ArcGIS StoryMaps
- Pandas, NumPy
- Public climate & zoning datasets

---

## Outcomes

- Demonstrated how **data-driven urban planning** can inform climate resilience
- Produced a reproducible modeling approach for future city-scale analysis
- Created a framework adaptable to other neighborhoods and cities

---

## References

- YMPJ BOA Report
- EJNYC Mapping Tool
- Google Earth Engine LST Data
- CESM2 Data
- Neighborhood Factors
- Surface Air Temp Differences
- LST relationship looseness and temperature differences
- GUHI to SUHI temperature differences
- Average Air Temperature in Central Park
- Tree Canopy effect on temperature
- Impervious Space effect on temperature study 1
- Impervious Space effect on temperature study 2
- NYC 2025 Monthly Air Temperatures  
- Reflective Roofs effect on temperature study 1
- Reflective Roofs effect on temperature study 2
- Reflective Roofs effect on temperature study 3
- Green Roofs effect on temperature study 1
- Green Roofs effect on temperature study 2
- Green walls effect on temperature
- Community gardens effect on temperature
- NYC Street Design Manual
- NYC Stormwater Manual
- NYC Local Law 92 and 94

---

*This project was developed for educational and research purposes as part of the AMNH Urban Futures Hackathon.*
