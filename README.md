# Inclusiveness-Index-Cities-in-Yangtze-River-Economic-Belt
# City-Level Panel Dataset (2008–2019)
## Overview
This dataset contains a balanced city–year panel for Chinese cities from **2008 to 2019**.
All variables and city names are provided in **English**, following standard academic conventions.

## Structure
- **Unit of analysis**: City–year
- **Time span**: 2008–2019
- **Key identifiers**:
  - `id`: City administrative code
  - `city`: City name (official English spelling)
  - `year`: Year

## Indicators
The dataset includes **17 Secondary indicators (Meso) (x1–x17)** with corresponding standardized values and scores:
- `x1`–`x17`: Raw indicator values  
- `sx1`–`sx17`: Min–max standardized indicators  
- `w1`–`w17`: Indicator weights  
- `score1`–`score17`: Weighted indicator scores  

A composite score is also provided:
- `Score`: Overall composite index

## Data Processing Notes
- Missing years were completed using city-specific linear interpolation to ensure a balanced panel.
- Indicator construction and standardization follow a consistent structure across all years.

## Usage
The dataset is provided in CSV format and can be directly used in:
- Python (pandas)
- R
- Stata

## Citation
If you use this dataset, please cite the associated study or repository.

