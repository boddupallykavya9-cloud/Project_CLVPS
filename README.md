# Customer Lifetime Value Prediction & Segmentation

## Overview

This project predicts and segments Customer Lifetime Value (LTV) using raw e-commerce transactional data. It demonstrates feature engineering, model comparison (Linear Regression, Random Forest, XGBoost), and business-oriented customer segmentation for actionable insights.

***

## Files

- **CLVPM.ipynb:** Main code notebook (Jupyter/Colab)  
- **CLVPM.ipynb - Colab.pdf:** Notebook PDF export  
- **CLVPS_report.docx:** Project summary report (1–2 pages)  
- **customer_ltv_segments.csv:** Final output—customer LTV scores and segments  
- **Visualizations (.png):** Customer segments, feature importance, model comparison, predicted LTV distribution

***

## Dataset

This project uses the [Retailrocket recommender system dataset](https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset) (Kaggle), a large-scale, anonymized collection of e-commerce user events (views, cart adds, purchases) and product/item info from a real retailer.

- **Source:** Retailrocket, Kaggle  
- **Core columns:** `visitorid` (user), `event_time`, `event`

Data was preprocessed and aggregated per-customer for LTV prediction.

***

## Project Steps

1. **Data Cleaning & Feature Engineering:**  
   - Created recency, tenure, and average order value/frequency per customer  
2. **Model Training:**  
   - Compared Linear Regression, Random Forest, and XGBoost on train/test splits  
3. **Evaluation:**  
   - Used MAE and RMSE metrics to select the best model  
4. **Segmentation:**  
   - Grouped customers into High/Medium/Low LTV segments by quantiles  
5. **Visualization & Export:**  
   - Plotted feature importance, segment bars, LTV distributions, and exported results

***

## Tools Used

- Python 3 (Colab/Jupyter)
- pandas, numpy
- matplotlib, seaborn
- scikit-learn, xgboost

***

## How to Use

1. *Clone or Download* this repository.
2. Open CLVPM.ipynb in Jupyter or Google Colab.
3. Run all cells sequentially to reproduce:
    - Data cleaning and feature engineering from raw transactions.
    - Model building (linear, random forest, XGBoost), automatic evaluation and comparison.
    - Customer scoring, segmenting, and visualization.
    - Export of all deliverables.
4. For quick review, view the PDF and Word report.
5. Download project outputs if needed.

## Results

Random Forest was selected as the best model due to the lowest error scores. The project provides CSVs, segments, and plots that enable data-driven retention and targeting strategies.

***

