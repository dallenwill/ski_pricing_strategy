# Ski Pricing Strategy Project

## Overview
This project builds a machine-learning model to recommend a fair weekend ticket price for a target ski resort. The model uses historical resort data, weather features, seasonal indicators, and engineered transformations to estimate an appropriate price.

The final model recommends a ticket price of **$94.58**, compared to the resort’s current price of **$81**.

---

## Project Goals
- Analyze factors that influence ski ticket prices  
- Compare multiple regression models  
- Select the best model using cross-validation  
- Predict a recommended price for the target resort  

---

## Data
The project uses processed and engineered features generated in earlier steps of the pipeline.

Key artifacts include:
- Transformed training/validation data  
- Feature names  
- Target resort feature vector  

Raw data is excluded for size/privacy reasons.

---

## Tools
- Python  
- NumPy, Pandas  
- Scikit-learn  
- Jupyter Notebook  

---

## Workflow
1. **Problem Definition**  
2. **Data Wrangling**  
3. **EDA**  
4. **Feature Engineering**  
5. **Modeling & Comparison**  
6. **Model Selection & Final Prediction**  

---

## Notebooks
- `sps_01_problem_definition.ipynb`  
- `sps_02_data_wrangling.ipynb`  
- `sps_03_eda.ipynb`  
- `sps_04_feature_engineering.ipynb`  
- `sps_05_modeling.ipynb`  

---

## Final Result
- **Current Price:** $81  
- **Model-Recommended Price:** **$94.58**  
- **Selected Model:** Ridge Regression (α = 1)

---

## Author
**Dallen Huang**  
Los Angeles, CA  
GitHub: [dallenwill](https://github.com/dallenwill)