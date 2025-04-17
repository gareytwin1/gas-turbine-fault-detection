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

Great idea! Adding `venv` support will help users who prefer **pure Python environments** without Conda. Here's the updated section for your `README.md`:

---

## Setting Up the Environment

This project supports both **Conda** and **Python virtual environments (venv)**.

---

### Option 1: Using `conda` (Recommended)

Create the environment from `environment.yml`:

```bash
conda env create -f environment.yml
```

Or from an exact export file (`environment.txt`):

```bash
conda create --name turbine_fault_env --file environment.txt
```

Activate it:

```bash
conda activate turbine_fault_env
```

Update an existing env:

```bash
conda env update -f environment.yml --prune
```

---

### Option 2: Using `venv` (Python Virtual Environment)

If you prefer `venv`:

1. **Create the environment**:

   ```bash
   python3 -m venv venv
   ```

2. **Activate the environment**:

   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```

3. **Install dependencies** from `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

4. (Optional) **Freeze dependencies** for later use:

   ```bash
   pip freeze > requirements.txt
   ```




