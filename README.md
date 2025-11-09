
# Customer Lifetime Value Prediction & Segmentation

## Overview

This project presents a complete pipeline to predict and segment Customer Lifetime Value (LTV) using transactional data. It includes end-to-end data processing, feature engineering, model training and selection, segmentation, and business visualization. Outputs support effective customer targeting and business decision-making.

***

## Repository Structure

- **CLVPM.ipynb:** Main Jupyter/Colab notebook with all code, steps, and analysis (run this to reproduce project).
- **CLVPM.ipynb - Colab.pdf:** PDF export of the main notebook.
- **CLVPS_report.docx:** 1–2 page summary project report (suitable for submission).
- **customer_ltv_segments.csv:** Final CSV with customer IDs, predicted LTV values, and segment labels.
- **Visualizations/Plots:**
    - `Customer Segments Count.png` – Barplot of segment counts
    - `Feature Importance Plot (Random Forest).png` – Model feature importances
    - `Model Comparison.png` / `Model Comparison2.png` – MAE/RMSE comparison across models
    - `Predicted LTV Distribution.png` – Histogram of predicted LTV values

***

## How to Use

1. **Clone or Download** this repository.
2. Open `CLVPM.ipynb` in Jupyter or Google Colab.
3. Run all cells sequentially to reproduce:
    - Data cleaning and feature engineering from raw transactions.
    - Model building (linear, random forest, XGBoost), automatic evaluation and comparison.
    - Customer scoring, segmenting, and visualization.
    - Export of all deliverables.
4. For quick review, view the PDF and Word report.
5. Download project outputs if needed.

***

## Main Steps

1. **Data Loading & Cleaning**
2. **Feature Engineering:** Recency, tenure, average order value per customer.
3. **Model Training:** Linear Regression, Random Forest, XGBoost.
4. **Model Evaluation:** MAE, RMSE, and comparison plots.
5. **LTV Prediction & Segmentation:** Using best model; customers segmented via quantiles.
6. **Visualization:** Segment distribution, feature importance, LTV histogram, model metrics.
7. **Export:** CSV with scores & segments, plots, and project report.

***

## Tools & Libraries

- Python, pandas, numpy
- matplotlib, seaborn
- scikit-learn
- xgboost
- Jupyter/Colab

***

## Results & Business Value

- **Random Forest** achieved the lowest MAE/RMSE, and was selected as the final model.
- Segmenting customers by predicted LTV supports:
    - Personalized outreach for high-value customers.
    - Data-driven retention and marketing for medium/low-value groups.
    - Efficient business resource allocation.

