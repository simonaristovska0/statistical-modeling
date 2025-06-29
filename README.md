# Statistical Modeling Repository

This repository contains two of projects developed for the course of Statistical Modeling @ FCSE.

## Projects Overview

### 1. Life Tables Analysis (Main Project)  
A deep dive into historical mortality patterns in Sweden from 1751 to 2023. We construct life tables, estimate age‐specific hazard rates, and compare male and female mortality over time.

**Contents**  
- `mortality_analysis.ipynb` – Jupyter notebook with full data processing, analysis steps, and visualization code  
- `datasets/`  
  - `mortality_raw.csv` – Raw mortality counts and exposures by age, year, and gender  
  - `population_raw.csv` – Population denominators  
- `Документација.pdf` – Written report summarizing methodology, key findings, and interpretation  
- `presentation.pdf` – Slide deck for an oral presentation  
- `requirements.txt` – Exact package versions used for reproducibility  

**Key Features**  
1. **Data Cleaning & Harmonization**  
   - Parsing Human Mortality Database downloads  
   - Converting to tidy format for analysis  
2. **Life Table Construction**  
   - Calculation of \(q_x\), \(l_x\), \(d_x\), \(e_x\)  
   - Visualization of survivorship curves  
3. **Hazard Rate Estimation**  
   - Smooth hazard functions by age and cohort  
   - Comparison of male vs. female mortality trends  
4. **Gender Differences**  
   - Heatmaps of log mortality differences  
   - Age‐period‐cohort decompositions  

### 2. Auto MPG Regression Project (ISLR Lab)

A hands-on implementation inspired by Lab 3 from *An Introduction to Statistical Learning*. This project investigates how vehicle characteristics influence fuel efficiency (mpg) using linear, multiple, and polynomial regression on the Auto dataset.

**Contents**
- `linear_models_auto.ipynb` – Jupyter Notebook with code for fitting and evaluating simple, multiple, and polynomial regression models
- `Документација.pdf` – Detailed report including statistical summaries, \(R^2\)/adjusted \(R^2\), ANOVA tables, and model diagnostics

**Key Analyses**
1. **Simple Regression** – mpg vs. horsepower, slope interpretation, residuals
2. **Multiple Regression** – adding weight, acceleration, displacement; VIF checks
3. **Polynomial Models** – quadratic fits for horsepower, ANOVA comparison
4. **Model Evaluation** – train/test split, RMSE on unseen data
5. **Visualizations** – scatter plots, fitted curves, leverage diagnostics


## Getting Started

### Prerequisites
- Python 3.8+  
- Virtual environment tool (venv, conda, etc.)  

### Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/statistical_modeling.git
   cd statistical_modeling
