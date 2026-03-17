# VLCIS-Rwanda: National Virtual Climate Observation System
![MIT License](https://img.shields.io/badge/license-MIT-green)
## Executive Summary
VLCIS-Rwanda is an AI-powered national virtual climate system providing high-resolution (3 km) weather and air quality data across Rwanda. With 1,543 virtual stations, VLCIS-Rwanda addresses gaps in physical meteorological infrastructure, supports climate resilience, and informs decision-making for agriculture, urban planning, disaster risk management, and policy-making.
This system is aligned with international standards and contributes to initiatives by the **World Meteorological Organization (WMO)** and the **African Union (AU)**.

---

## Key Features
- 1,543 virtual stations covering the entire country  
- Hourly and daily climate and air quality outputs  
- 17 climate variables (temperature, precipitation, humidity, wind, solar radiation, etc.)  
- 7 air quality indicators (PM2.5, PM10, NO2, O3, CO, SO2, AQI)  
- AI-driven predictive modeling and spatial interpolation  
- Fully virtual system—no physical sensors required  
- Open data access for research, policy, and commercial applications  

---

## System Architecture
1. **Data Collection:** Integrates open datasets from satellites, numerical weather models, and environmental sources  
2. **Data Processing:** AI-based spatial interpolation, quality control, and predictive modeling  
3. **Outputs:**  
   - Climate maps (temperature, rainfall, humidity, wind)  
   - Air quality dashboards and alerts  
   - CSV/JSON datasets for researchers and stakeholders  

---

## Installation & Usage
```bash
# Clone the repository
git clone https://github.com/WCSS-Ltd/VLCIS-Rwanda.git

# Install dependencies
pip install -r requirements.txt

# Run Python scripts for data processing and visualization
python scripts/run_model.py
