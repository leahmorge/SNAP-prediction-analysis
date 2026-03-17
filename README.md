# SNAP 2018 Prediction & Geospatial Analysis

## Overview
This project uses historical SNAP (Supplemental Nutrition Assistance Program) Quality Control data to generate predictions for SNAP participation and benefit-related variables. Using data from 2007 and 2017, a model was developed and applied to 2018 data to estimate patterns of participation and deduction across the United States.

The results are visualized in QGIS to examine geographic variation in predicted SNAP outcomes and the influence of housing-related costs.

---

## Objectives
- Develop a predictive approach using historical SNAP data  
- Estimate SNAP participation and benefit-related variables for 2018  
- Analyze how housing costs influence SNAP benefit calculations  
- Visualize predicted outcomes across U.S. states using geospatial mapping  

---

## Tools & Technologies
- QGIS (geospatial visualization and mapping)  
- Python (data processing and modeling)  
- SNAP Quality Control (QC) Data  

---

## Data Sources
Raw datasets are not included due to file size limitations.  
See the `data/data_sources.md` file for full details on data access and sources.

---

## Methods
1. SNAP Quality Control datasets from 2007 and 2017 were cleaned and prepared using Excel and Python.  
2. These datasets were used to identify patterns and support predictive modeling.  
3. The model was applied to 2018 data to generate predicted values for SNAP participation and deduction-related variables.  
4. Predicted outputs were joined to state boundary data and visualized in QGIS.  

---

## Key Visualizations & Findings

### Predicted SNAP Participation
Predicted SNAP participation appears highest in several southeastern and southwestern states, suggesting stronger demand for food assistance in these regions relative to the national average.

### Shelter Deductions
States with higher housing costs show larger predicted shelter deductions, indicating that housing expenses play a significant role in SNAP benefit calculations.

### Excess Shelter Deductions
Excess shelter deductions are highest in states where housing costs frequently exceed SNAP program thresholds, highlighting the impact of cost-of-living differences on benefit calculations.

---

## Repository Contents

- `code/` – Data processing and modeling scripts  
- `data/` – Documentation of data sources  
- `images/` – Map outputs
- `QGIS SNAP Predictions.pdf` – Analysis/Findings
- `README.md` – Project overview  

---

## Why This Matters
Predicting SNAP participation and benefit patterns can help inform policy decisions, resource allocation, and program accessibility. By combining predictive analysis with geospatial visualization, this project highlights how regional cost differences—particularly housing—may influence food assistance needs.

---

## Author
Leah Morgenstern
