# Diabetes Prediction Data Preparation

## Project Overview
This project prepares a clean dataset to improve diabetes prediction model accuracy.
It addresses missing data, outliers, biological inconsistencies, and feature scaling.

## Features
- Missing value handling (KNN + median)
- Outlier capping (IQR)
- Feature engineering (Age, BMI, Glucose categories)
- Encoding + Scaling
- PCA visualization

## Files
- GOOGLE_COLLAB_DIABETS_cleaning python code: Reusable preprocessing code
- final_cleaned_diabetes.csv: Cleaned dataset
-

- correlation_heatmap.png, pca_explained_variance.png: Visuals

## Usage
1. Run the GOOGLE_COLLAB_DIABETS_cleaning python code.ipnyb:
   python GOOGLE_COLLAB_DIABETS_cleaning python code.ipnyb "Diabetes Missing Data.csv" "final_cleaned_diabetes.csv"
2. Outputs will be saved automatically in your working directory.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Imbalanced-learn
- Matplotlib / Seaborn

## Expected Outcome
- Clean, imputed, and scaled diabetes dataset

- PCA and correlation visualizations

