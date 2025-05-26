# 🗺️ Forest Fire Mapping Dataset – Southern Quebec

## 📌 Overview
This dataset provides multi-source, long-term mapping of forest fires in **southern Quebec**, covering both managed and unmanaged forest areas. It supports **forest management**, **fire regime analysis**, and **climate impact research**.

---

## 🧭 Geographic Coverage
- Entire **southern Quebec**, including:
  - Managed forest zones
  - Northern unmanaged zones (partial coverage)

---

## ⏳ Temporal Coverage
- **Ancient Fires:** Late 19th century – 1975
- **Simplified & Origin Mapping:** 1972 – Present
- **Detailed Burn Mapping:** 1976 – Present
- **Fire Regime Zones:** Based on data from 1890 – 2020

---

## 📂 Data Types & Layers

### 🔥 1. Detailed Burn Mapping (1976–Present)
- Burn types: *Total*, *Partial*
- Includes **burn pattern classes**
- Mapping resolution: as fine as **0.1 ha**
- Partial coverage in northern zones

### 🧭 2. Simplified Fire Contours (1972–Present)
- Simplified **external contours** only
- GPS/Geospatial system ready

### ⚡ 3. Fire Origins (1972–Present)
- Metadata: **Date, Cause (Human/Lightning), Protection Zone**
- Covers **all of Quebec**

### 🕰️ 4. Ancient Fires (Late 1800s–1975)
- Based on forest inventories and ecoforest maps
- **Fire scar analysis** and archival data
- Regions: Saguenay, Bas-Saint-Laurent, Gaspésie, Abitibi, Mauricie, Lanaudière, Laurentides

### 🧩 5. Fire Regime Mapping (1890–2020)
- 13 distinct **fire regime zones**
- Based on:
  - Historical burned area
  - **Environmental variables** (physiography, species composition, ignition sources)

---

## 🧾 Sample Data Fields

| Field Name           | Description                                      |
|----------------------|--------------------------------------------------|
| `Fire_ID`            | Unique identifier for each fire                  |
| `Year`               | Year the fire occurred                           |
| `Area_burned`        | Burned area in hectares                          |
| `Burn_type`          | Total / Partial                                  |
| `Burn_pattern_class`| Spatial pattern classification                   |
| `Ignition_source`    | Human or Lightning                               |
| `Protection_zone`    | Fire management zone (e.g., SOPFEU)              |
| `Fire_regime_zone`   | Assigned fire regime area                        |
| `Data_source_type`   | Satellite, aerial photo, field survey, etc.      |

---

## 🧠 Applications
- Modeling **post-fire regeneration**
- Studying **ecosystem dynamics**
- Supporting **special forest management plans**
- Forecasting future fire risks under **climate change**

---

## 📚 Reference
> Forest Research Paper No. 189 – *Zoning Fire Regimes in Southern Quebec* (Coming Soon)
