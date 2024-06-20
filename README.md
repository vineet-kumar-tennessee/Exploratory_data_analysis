# Heart Disease Dataset EDA

This repository contains an Exploratory Data Analysis (EDA) script for the Heart Disease dataset from the UCI Machine Learning Repository.

## Dataset

The dataset used in this analysis is the [Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease) from the UCI Machine Learning Repository. The dataset contains 76 attributes, but all published experiments refer to using a subset of 14 of them. This script uses the Cleveland dataset, which has been used for most of the experiments.

## Steps Included in the EDA

1. **Variable Identification**
2. **Univariate Analysis**
    - Age Distribution
    - Resting Blood Pressure Distribution
    - Sex Distribution
3. **Bivariate Analysis**
    - Correlation Matrix
    - Age vs Resting Blood Pressure
    - Sex vs Cholesterol Level
    - Positive Correlation (Age vs Max Heart Rate Achieved)
    - Negative Correlation (Age vs ST Depression)
    - No Correlation (Cholesterol Level vs Chest Pain Type)
4. **Outlier Treatment**
    - Outliers in Resting Blood Pressure
5. **Missing Value Treatment**
6. **Variable Transformation**
    - Log Transformed Cholesterol Level Distribution
7. **Variable Creation**
8. **Pair Plots**
9. **Feature Distributions**
10. **Categorical Feature Analysis**
    - Sex Count
    - Chest Pain Type Count
    - Fasting Blood Sugar Count
    - Resting ECG Count
    - Exercise Induced Angina Count
    - Slope of the Peak Exercise ST Segment Count
    - Number of Major Vessels Colored by Flourosopy Count
    - Thalassemia Count
11. **Advanced Outlier Detection (Z-Score Method)**
12. **Missing Value Visualization**
    - Missing Values Matrix
    - Missing Values Bar
13. **Correlation with Target Variable**
14. **Heatmap of Feature Correlations**

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-eda.git
    cd heart-disease-eda
    ```

2. Ensure you have the necessary libraries installed:
    ```bash
    pip install pandas numpy matplotlib seaborn missingno scipy
    ```

3. Run the Python script:
    ```bash
    python eda_heart_disease.py
    ```

## Visualizations

The script generates several visualizations using seaborn to help understand the dataset, including histograms, violin plots, count plots, joint plots, regression plots, KDE plots, pair plots, and heatmaps.

