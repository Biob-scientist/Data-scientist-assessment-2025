# Project Structure Overview

This document summarizes the structure of the project folders and the purpose of each component.

---

## Folder Summary

### 1. `Assessment_A` - ETL & Map Production
- **Purpose**: Handles data extraction, transformation, and loading (ETL), as well as map visualizations.  
- **Contents**:
  - Python scripts for cleaning and processing raw data
  - Map production notebooks
  - Any supporting CSV or shapefiles for visualization
- **Notes**:
  - All data wrangling steps and map visualizations are contained here.
  - The folder is independent of the machine learning workflow.

---

### 2. `Assessment_B` - Machine Learning
- **Purpose**: Implements the predictive modeling workflow for COVID-19 screening.  
- **Contents**:
  - **EDA Notebook**: Exploratory Data Analysis, feature selection, statistical tests, and visualizations.  
  - **ML Notebook**: Machine Learning model training, evaluation, and performance comparison.  
  - Supporting datasets and preprocessing scripts (if any)  
- **Notes**:
  - Focused on developing, testing, and interpreting predictive models.
  - The notebooks are structured to ensure reproducibility.

---

## Future Expansion
- **Assessment_C**: Placeholder for future work, could include:
  - Deployment pipelines  
  - Advanced analytics  
  - Extended data sources

---

## Folder Hierarchy Example
