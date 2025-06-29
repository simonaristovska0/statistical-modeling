# Statistical Modeling Repository

This repository contains two complementary projects in statistical modeling and data visualization, both implemented in Python and focused on demographic and population data analysis.

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

### 2. Linear Models Project (ISLR Lab)  
A hands-on implementation of Chapter 3 labs from *An Introduction to Statistical Learning*. We explore polynomial regression, model diagnostics, and prediction accuracy on real‐world population data.

**Contents**  
- `linear_models.ipynb` – Notebook with code for fitting and evaluating linear, polynomial, and interaction‐term models  
- `Документација.pdf` – Lab report including statistical summaries, \(R^2\)/adjusted \(R^2\), and diagnostic plots  
- `requirements.txt` – Library list for this project  

**Key Analyses**  
1. **Simple Linear Regression**  
   - Fitting population vs. year  
   - Residual analysis and inference on slope  
2. **Polynomial Regression**  
   - Comparing quadratic and cubic fits  
   - Testing for nonlinearity (F-tests)  
3. **Interactions & Higher-Order Terms**  
   - Adding interaction between predictors  
   - Interpretation of coefficients  
4. **Model Selection**  
   - Cross‐validation to choose polynomial degree  
   - Bias-variance tradeoff visualization  

## Getting Started

### Prerequisites
- Python 3.8+  
- Virtual environment tool (venv, conda, etc.)  

### Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/statistical_modeling.git
   cd statistical_modeling
