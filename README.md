# Energy Efficiency and Building Performance – Statistical Analysis in R

## Project Overview

This project analyzes the energy performance of residential buildings using simulated architectural design characteristics. The objective is to investigate how geometric and structural features influence energy demand, focusing on heating load (Y1) and cooling load (Y2).

The analysis includes data preprocessing, exploratory data analysis, distributional analysis, hypothesis testing, supervised learning, and unsupervised learning techniques.

This project was completed individually as part of the course *Statistical Programming with R*.

---

## Dataset Description

The dataset consists of simulated cross-sectional data for 768 residential buildings.

- Unit of observation: Building  
- Data structure: Cross-sectional  
- Number of observations: 768  

### Design Variables

- X1: Relative Compactness  
- X2: Surface Area  
- X3: Wall Area  
- X4: Roof Area  
- X5: Overall Height  
- X6: Orientation  
- X7: Glazing Area  
- X8: Glazing Area Distribution  

### Response Variables

- Y1: Heating Load  
- Y2: Cooling Load  

The dataset allows for analyzing how architectural design choices affect building energy efficiency.

---

## Methodology

The project follows a structured and reproducible statistical workflow.

### 1. Data Cleaning and Preprocessing

- Verification of variable types and ranges  
- Correlation analysis among design variables  
- Examination of multicollinearity  
- Scaling considerations when necessary  

All preprocessing steps are implemented programmatically in R.

---

### 2. Exploratory Data Analysis (EDA)

- Distribution analysis of heating and cooling loads  
- Visualization of relationships between building characteristics and energy demand  
- Analysis of trade-offs between heating and cooling requirements  

Graphical analysis was conducted using ggplot2.

---

### 3. Distributional Analysis and Probability

- Study of the joint distribution of heating and cooling loads  
- Examination of variability and dependence  
- Estimation of probability of high heating demand:

  **P(YH > 30) = 0.2942**

This indicates that approximately 29.4% of buildings exhibit high heating load.

---

### 4. Hypothesis Testing

Statistical hypotheses were formulated to test the impact of architectural characteristics on energy demand.

Appropriate statistical tests were selected and interpreted in the context of energy efficiency and sustainable design.

---

### 5. Supervised Learning

A prediction task was defined using heating load as the primary response variable.

The following models were implemented and compared:

- Multiple Linear Regression  
- Alternative model specifications  

Models were evaluated using:

- R²  
- Adjusted R²  
- F-statistic  
- p-values  
- Residual diagnostics  

The final model was selected based on statistical significance and explanatory power.

---

### 6. Unsupervised Learning

Unsupervised learning techniques were applied to identify groups of buildings with similar energy performance profiles.

- Variable selection was justified based on energy relevance  
- Preprocessing steps were implemented prior to clustering  
- Clusters were interpreted in terms of building design characteristics and energy efficiency  

The clustering results provide insight into different building energy performance categories.

---

## Key Findings

- Surface Area and Glazing Area significantly influence heating demand.  
- Architectural design plays a central role in determining energy efficiency.  
- A substantial proportion of buildings exhibit high heating demand.  
- Clustering analysis reveals distinct groups of buildings with different energy performance profiles.

---

## Tools and Technologies

- R  
- ggplot2  
- dplyr  
- Statistical modeling techniques  
- Hypothesis testing  
- Clustering methods  

---

## Reproducibility

- The dataset was not manually modified.  
- All preprocessing steps were implemented programmatically.  
- The analysis runs from start to finish without errors.  
- Code is fully documented and reproducible.

---

## Project Structure

energy-efficiency-analysis/

- data/ → Dataset  
- scripts/ → Main analysis script  
- outputs/ → Generated plots and model results  
- report/ → Final written report  
- README.md  

---

## Author

Jaures Kuete Tchinda  
B.Sc. Data Analytics in Economics and Business  
RPTU Kaiserslautern-Landau