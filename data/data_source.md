# Data Sources for SNAP Prediction Analysis

## Data Access
Due to file size limitations, the raw datasets are not included in this repository. All data used in this project is publicly available through the sources listed below.

## Primary Data Source
- Source: Supplemental Nutrition Assistance Program (SNAP) Quality Control Database  
- Provider: U.S. Department of Agriculture (USDA), Food and Nutrition Service  
- Access: https://snapqcdata.net/  
- Original Data Portal: https://www.fns.usda.gov/snap/qc/database  

## Datasets Used

### Model Development
- **2007 Data:** `qcfy2007_spss.zip`  
- **2017 Data:** `qcfy2017_csv.zip`  

These datasets were used to explore historical patterns and support model development.

### Prediction Dataset
- **2018 Data:** `qcfy2018_csv_0.zip`  

This dataset was used to generate predictions and evaluate model outputs.

## Notes
- Data files were downloaded directly from the SNAP Quality Control database.  
- Cleaning and processing was performed through Python.
