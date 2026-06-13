# Identifying Optimal Locations for New Public Parks in Hamilton City Using GIS

## Project Overview

This project uses Geographic Information Systems (GIS) to identify optimal locations for new public parks in Hamilton, New Zealand. The analysis focuses on improving equitable access to green spaces by locating high-population-density areas that are currently underserved by existing parks.

The project was completed as part of the **GEOGY558 - Applied Geographic Information Systems for Research and Planning** course at the University of Waikato.

---

## Objectives

- Analyze the spatial distribution of existing public parks in Hamilton.
- Identify areas outside the service range of current parks.
- Locate high-density residential areas lacking access to green spaces.
- Determine suitable locations for future park development.
- Support evidence-based urban planning and sustainable city development.

---

## Study Area

Hamilton City, New Zealand

---

## Data Sources

- **Population Data (2024)** – Statistics New Zealand
- **Reservoirs and Park Data** – Hamilton City Council Open Data Portal
- **Building Footprints** – Land Information New Zealand (LINZ)
- **Road Network Data** – Hamilton Transport GIS Database

---

## GIS Tools and Techniques

The following ArcGIS Pro tools were used:

- Field Calculator
- Buffer Analysis (300m Service Area)
- Erase Tool
- Select by Attribute
- Intersect Tool
- Export Features
- Summary Statistics
- Spatial Overlay Analysis

---

## Methodology

### 1. Calculate Population Density
Population density was calculated for each spatial unit using census population data.

### 2. Create Park Accessibility Buffers
A 300-meter buffer was generated around existing parks to represent walking-distance accessibility.

### 3. Identify Underserved Areas
Areas outside the park service buffers were extracted using the Erase tool.

### 4. Select High-Density Areas
Population zones above the median density threshold were identified.

### 5. Overlay Analysis
High-density areas were intersected with underserved areas to locate priority zones.

### 6. Remove Developed Land
Building footprints were erased from candidate locations to identify open land suitable for park development.

### 7. Generate Final Park Suitability Map
Remaining areas were classified as optimal locations for new public parks.

---

## Results

The analysis identified multiple underserved locations across Hamilton that:

- Have high population density
- Lack convenient access to existing parks
- Are free from existing building footprints

A suburb-level summary revealed proposed park locations distributed across 17 different suburbs, indicating a broad need for improved green space accessibility throughout the city.

---

## Key Findings

- Park accessibility is uneven across Hamilton.
- Several densely populated neighborhoods are outside the recommended walking distance to a public park.
- GIS-based spatial analysis can effectively support urban planning and green infrastructure development.

---

## Limitations

- Euclidean buffers were used instead of network-based travel distances.
- Land ownership and zoning data were not included.
- Population figures may not reflect recent growth patterns.
- Environmental constraints such as flood risk and terrain were not assessed.

---

## Future Improvements

- Network-based accessibility analysis
- Integration of zoning and cadastral datasets
- Inclusion of demographic-specific needs
- Environmental suitability assessment
- Community consultation and stakeholder engagement

---

## Software Used

- ArcGIS Pro
- ArcGIS Online
- Microsoft Excel

---

## Project Report

[Project Report](MyProject_new/Project_report.pdf)

---

## Author

**Sriarani Surenther**

Master of Information Technology (First Class Honours)  
University of Waikato  
GitHub: https://github.com/sriarani16
LinkedIn: https://www.linkedin.com/in/sriarani-surenther
