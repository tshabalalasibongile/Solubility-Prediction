# Solubility Prediction

## Overview
This project applies machine learning techniques to predict the solubility of chemical compounds based on their molecular descriptors. The dataset (Delaney) contains 1,128 compounds represented in SMILES notation, with experimentally measured solubility values (`logS`) as the target.

## Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (Linear Regression)

## Project Tasks
### 1. Data Exploration
- Checked dataset structure and summary statistics.
- Visualized distributions and outliers using histograms and boxplots.

### 2. Data Preprocessing
- Handled categorical features (Compound ID, SMILES) by encoding.
- Scaled numerical features using StandardScaler.
- Split dataset into training and test sets (80-20 split).

### 3. Model Training
- Trained a Linear Regression model on molecular descriptors to predict solubility.

### 4. Model Evaluation
- Evaluated the model using MSE, RMSE, and R².
- Visualized predicted vs actual solubility and residual distributions.

### 5. Feature Importance
- Identified key molecular descriptors affecting solubility:
  - Polar Surface Area (positive impact)  
  - Molecular Weight (negative impact)  
  - Number of Rings (negative impact)

## Key Learnings
- Linear regression provides a simple yet effective baseline for predicting solubility.  
- Feature scaling ensures consistent model performance.  
- Outliers and skewed distributions can significantly affect model accuracy.  
- Visualization of data and residuals is essential for understanding model performance.

## How to Run
1. Clone this repository.  
2. Install dependencies: `pip install -r requirements.txt`  
3. Open the notebook `solubility_prediction.ipynb` in Jupyter or Google Colab.  

## Repository Structure

