# Step-by-step guides for producing geospatial SDGs in QGIS
This repository hosts a collection of practical, step-by-step guides for modeling Sustainable Development Goal (SDG) indicators using QGIS, open data, and geospatial techniques. The materials were developed as part of the ESCAP project “The 2030 Data Decade – Strengthening the institutional capacity of national statistical offices in Asia and the Pacific to use innovative, new and big data sources for official statistics.” This project was funded by the 2030 Agenda subfund of the UN Peace and Development Trust Fund. 

These guides are intended to support National Statistical Offices (NSOs), GIS practitioners and policy analysts in integrating statistical and geospatial data to produce robust, repeatable analyses for SDG monitoring.

## Guides

### 1. **Modeling DEGURBA (Degree of Urbanization)**
- **[Download PDF](./KGZ_Degurba_QGISstepbystep_ESCAP.pdf)** (ENGLISH)
- **Focus:** Applying the Degree of Urbanization classification to map urban extent. 

### 2. **Modeling SDG 9.1.1: Rural Population Access to Roads**
- **[Download PDF](./KGZ_911_QGISstepbystepFinal_ENG_ESCAP.pdf)** (ENGLISH)
- **Focus:** Estimating the share of rural population within 2 km of all-season roads using OSM and population data.

### 3. **Modeling SDG 11.3.1: Ratio of Land Consumption rate to Population Growth**
- **[Download PDF](./KGZ_1131_QGISstepbystepFinal_ENG_ESCAP.pdf)** (ENGLISH)
- **Focus:** Comparing urban land expansion and population growth using time-series LULC and WorldPop data.

> 🗂 Russian-language versions of the guides will be available soon.

---

## Data

All required datasets for replicating the tutorials are included in the [`data/`](./data) folder. This includes:

- Administrative boundaries
- Population grids (WorldPop)
- Land Use Land Cover (Esri, 2017–2023)
- Road networks (OpenStreetMap and national sources)
- DEGURBA urban areas (derived using GHS-DUG Tool)
- Building footprints with population data

> 📌 All spatial datasets are preprocessed and projected to appropriate coordinate systems, ready to use in QGIS.

## Requirements

To follow the tutorials effectively, you should have:
- Basic experience with QGIS
- Familiarity with geospatial raster/vector data
- A machine with:
  - Intel i5/i7/i9 processor
  - Minimum 8–16 GB RAM (32 GB recommended)
  - Dedicated GPU (optional but helpful)

## Author & Contact

Developed by **Elena Hristev**, Consultant, UN ESCAP  
📧 escap-statistics@un.org

## License

This repository is intended for educational and institutional use. Attribution to the ESCAP project and the original author is requested when reusing or adapting the materials.
