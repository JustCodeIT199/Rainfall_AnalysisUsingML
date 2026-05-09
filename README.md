<div align="center">

<img src="https://img.shields.io/badge/Rainfall%20Analysis-Machine%20Learning-0EA5E9?style=for-the-badge&logo=cloud&logoColor=white" alt="Rainfall Analysis Banner" />

# Rainfall Analysis Using Machine Learning

**Statistical insights and model-based rainfall forecasting from historical climate data**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

</div>

---

## Overview

This project applies supervised machine learning techniques to analyze historical rainfall data, uncover trends, and generate predictive forecasts. By evaluating multiple regression models side by side, it identifies the best-performing approach for rainfall prediction — with real-world applications in agriculture, water resource management, and climate research.

---

## Objective

> Leverage machine learning to analyze historical rainfall patterns and produce reliable predictions that support smarter planning across agriculture, hydrology, and climate science.

---

## Machine Learning Models

| Model | Type | Use Case |
|-------|------|----------|
| **Linear Regression** | Parametric | Baseline trend modeling |
| **Decision Tree Regressor** | Tree-based | Non-linear pattern capture |
| **Random Forest Regressor** | Ensemble | Robust, high-accuracy prediction |
| **Support Vector Regression (SVR)** | Kernel-based | Complex boundary estimation |

---

## Libraries & Tools

| Category | Libraries |
|----------|-----------|
| **Data Processing** | `pandas`, `numpy` |
| **Visualization** | `matplotlib`, `seaborn` |
| **Machine Learning** | `scikit-learn` |
| **Environment** | Jupyter Notebook |

---

## Project Structure

```
Rainfall_AnalysisUsingML/
│
├── main_project_sem4.ipynb   # Main analysis and modeling notebook
├── rainfall_dataset.csv      # Historical rainfall dataset
├── requirements.txt          # Python dependencies
└── README.md
```

---

## Features

- **Exploratory Data Analysis (EDA)** — distribution plots, missing value handling, seasonal trends
- **Correlation Analysis** — heatmaps and feature relationship visualizations
- **Multi-Model Training** — train and compare four regression algorithms
- **Performance Evaluation** — R² Score, MAE, and RMSE across all models
- **Comparative Analysis** — side-by-side model benchmarking to identify the best predictor
- **Prediction on Unseen Data** — generate forecasts beyond the training set

---

## Model Evaluation Metrics

| Metric | Description |
|--------|-------------|
| **R² Score** | Proportion of variance explained by the model (higher = better) |
| **MAE** | Mean Absolute Error — average magnitude of prediction errors |
| **RMSE** | Root Mean Squared Error — penalizes large prediction errors more heavily |

---

## Getting Started

### Prerequisites

- Python 3.8+
- pip
- Jupyter Notebook

---

### 1. Clone the Repository

```bash
git clone https://github.com/JustCodeIT199/Rainfall_AnalysisUsingML.git
cd Rainfall_AnalysisUsingML
```

### 2. Set Up a Virtual Environment

```bash
python -m venv env

# macOS / Linux
source env/bin/activate

# Windows
env\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch the Notebook

```bash
jupyter notebook main_project_sem4.ipynb
```

---

## Workflow

```
Raw Rainfall Dataset (CSV)
        │
        ▼
  Data Cleaning & Preprocessing
  (missing values, outliers, encoding)
        │
        ▼
  Exploratory Data Analysis
  (trends, distributions, correlations)
        │
        ▼
  Model Training
  (Linear Regression, Decision Tree,
   Random Forest, SVR)
        │
        ▼
  Evaluation & Comparison
  (R², MAE, RMSE)
        │
        ▼
  Forecasting on Unseen Data
```

---

## Applications

- **Agriculture** — plan irrigation and sowing schedules based on rainfall forecasts
- **Water Resource Management** — anticipate reservoir levels and flood risk
- **Climate Research** — study long-term rainfall trends and anomalies
- **Urban Planning** — prepare infrastructure for seasonal rainfall variation

---

## Roadmap

- [ ] Add time-series models (LSTM, ARIMA) for sequential forecasting
- [ ] Interactive visualization dashboard (Plotly / Dash)
- [ ] Hyperparameter tuning with GridSearchCV
- [ ] Region-wise rainfall analysis
- [ ] Deployment as a web app with prediction API

---

## Authors

- [@JustCodeIT199](https://github.com/JustCodeIT199)
- [@Kshitij15042004](https://github.com/Kshitij15042004)

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---
