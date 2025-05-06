# 🚗 Road‑Accident‑Dashboard‑UK  
*An interactive Tableau project uncovering road‑safety insights across the United Kingdom.*

---

## 📊 Overview  
This project presents a comprehensive **Road Accident Analysis Dashboard** built in Tableau using real‑world accident data from the UK Department for Transport (DfT).  
The goal is to turn millions of raw accident‑and‑casualty records into actionable insights that help planners, campaigners, and citizens make Britain’s roads safer.

**What the dashboard delivers**

- **KPI Deck** – headline metrics for total accidents and casualties (fatal, serious, slight) with YoY deltas  
- **Severity Heatmap** – a UK map coloured by accident severity to pinpoint danger hotspots at a glance  
- **Vehicle‑Type Breakdown** – shows how cars, HGVs, bikes, and motorcycles contribute to accident counts and casualty severity  
- **Weather & Road‑Surface Impact** – reveals how rain, snow, fog, and surface conditions (wet, icy, dry) influence crash outcomes  
- **Interactive Filters** – slice the data by year, severity level, vehicle type, and road type to drill into patterns that matter to you

By surfacing the *where*, *when*, and *why* behind collisions, the dashboard supports evidence‑based road‑safety policies, targeted infrastructure upgrades, and public awareness campaigns.

---

## 🎯 Dashboard Highlights  

| Section | What you’ll uncover |
|---------|---------------------|
| **KPI Deck** | National totals for accidents & casualties (fatal, serious, slight) |
| **Severity Heatmap** | Geographic clustering of high‑risk locations |
| **Vehicle‑Type Impact** | Cars, trucks, bikes, motorcycles—who’s involved, where, and how badly |
| **Environmental Factors** | Weather and road‑surface conditions linked to severity |
| **Interactive Filters** | Year selector · Severity toggle · Vehicle type · Road type |

---

## 📌 Key KPIs  
- **Total Accidents**  
- **Total Casualties**  
- **Fatal Casualties**  
- **Serious Casualties**  
- **Slight Casualties**

---

## 🛠 Tech Stack  
| Stage | Tool | Purpose |
|-------|------|---------|
| Data prep | **Excel / Power Query** | Merge yearly CSVs, derive date parts, remove nulls |
| Viz | **Tableau 2023.3** | Build maps, calculated severity rates, parameter‑driven filters |
| Mapping | **Mapbox + OpenStreetMap** | Custom basemap & point clustering |
| Design | **Storytelling with Data** principles | Clear, colour‑blind‑friendly palette & hierarchy |

---

## 🔗 Live Dashboard  
**▶️ [Explore on Tableau Public](https://public.tableau.com/app/profile/karishma.sawant/viz/RoadAccident_17395459826550/RoadAccidentDashboard)**

---

## 🖼 Preview  

#### 📊 KPI Overview  
![Road Accident Overview](Road%20Accident-Overview%285%29.png)

#### 💀 Fatal Casualties  
![Road Accident Fatal Casualties](Road%20Accident%20Fatal%20Casualties.png)

#### 🚑 Serious Casualties  
![Road Accident Serious Casualties](Road%20Accident%20Serious%20Casualties.png)

#### 🤕 Slight Casualties  
![Road Accident Slight Casualties](Road%20Accident%20Slight%20severity%286%29.png)

---

## 📦 Dataset  
- **Source**: UK Department for Transport – Road Safety Data (2019–2022)  
- **Time Range**: 4 years (2019, 2020, 2021, 2022)  
- **Volume**: ≈ 680,000 accident records, ≈ 920,000 casualty entries  
- **Format**: CSV files merged via Power Query  


