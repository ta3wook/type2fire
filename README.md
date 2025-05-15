![type2fire banner](./assets/banner.png)

# type2fire

**Tree Type × Wildfire Risk**

A spatial data analysis project exploring how different forest types — particularly coniferous and broadleaf — relate to wildfire occurrence and damage in Korea, using public GIS datasets and Python-based visualization tools.

---

## 📊 Project Overview

Recent large-scale wildfires in Korea have highlighted the importance of understanding how forest composition affects wildfire vulnerability. Coniferous forests, rich in resin and low in moisture, are often more flammable than broadleaf forests. This project analyzes the relationship between forest type and wildfire occurrence, focusing on Seoul using GIS, GeoPandas, and Folium.

---

## 📂 Folder Structure

```bash
type2fire/
├── data/
│   ├── raw/                 # Original SHP/CSV files
│   └── processed/           # Geocoded & transformed data
├── notebooks/               # Jupyter notebooks (exploration, analysis)
├── src/                     # Utility scripts
├── output/
│   ├── maps/                # Folium HTML maps
│   └── figures/             # Visual charts/images
├── assets/                  # Banner image & supporting visuals
├── README.md                # You're here!
├── requirements.txt         # Python dependency list
├── .gitignore               # Git exclusions
└── LICENSE                  # MIT license
```

---

## 🔹 Features

* Spatial visualization of coniferous, broadleaf, and mixed forests (임상도)
* Geocoding of wildfire incidents using administrative addresses
* Overlay mapping of fire locations and forest type distribution
* Correlation analysis between forest composition and fire occurrence

---

## 🔧 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/type2fire.git
cd type2fire
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch notebooks

Use JupyterLab or VS Code to explore `notebooks/` step by step.

---

## 📖 Data Sources

* 서울특별시 산림 임상도 (산림청)
* 산불 발생 통계 데이터 (산림청 산불상황관제시스템)
* OpenStreetMap (Nominatim API for geocoding)

---

## 👨💻 Authors

* 남태욱 — Project lead, spatial analysis, visualization
* 박상재 — Wildfire geocoding, correlation analysis
* 황규상 — Forest data processing, reporting

---

## 📄 License

This project is licensed under the **MIT License**. See `LICENSE` for more details.

