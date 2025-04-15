# Fault Detection in Gas Turbine Engines using Sensor Data

## Overview

This project focuses on sensor data analysis for **fault detection and predictive maintenance** of industrial gas turbine engines. The core objective is to develop a **classification model** that can detect failures in gas compressors—an application highly relevant to **midstream pipeline operations**, where turbines drive compression systems.

## Dataset

**Source**: [Gas Turbine Engine Fault Detection Dataset on Kaggle](https://www.kaggle.com/datasets/ziya07/gas-turbine-engine-fault-detection-dataset)  
The dataset includes sensor readings like:
- Temperatures
- Pressures
- Rotational Speeds  
It also includes labeled fault types, making it ideal for supervised machine learning.

## Objectives

- Build classification models to detect and classify faults
- Engineer features such as pressure ratios, temperature differentials, and time-based deltas
- Apply outlier detection to identify sensor anomalies
- Use time-series segmentation to capture operational patterns over time

## Techniques and Tools

### Machine Learning Models
- Random Forest
- XGBoost
- Support Vector Machines

### Outlier Detection
- Isolation Forest
- DBSCAN

### Time-Series Analysis
- Windowing and segmentation
- Trend decomposition (optional for EDA)

### Python Libraries
- `scikit-learn`
- `xgboost`
- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`

## Value and Impact

This project supports **predictive maintenance** strategies to:
- Detect mechanical degradation early
- Reduce equipment downtime
- Enhance pipeline safety
- Lower operational costs

## Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/gas-turbine-fault-detection.git
   cd gas-turbine-fault-detection

