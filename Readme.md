# Rossmann Store Sales Analysis & Prediction

## Project Overview

This project explores historical sales data from Rossmann drug stores to identify sales patterns, examine promotional activity, and build regression models to predict daily sales for open stores.

The project combines exploratory data analysis (EDA) with introductory machine learning to demonstrate practical Python skills in retail analytics.

## Business Objectives

- Analyze sales trends across months, weekdays, and store types.
- Compare sales and customer activity on promotional and non-promotional days.
- Investigate differences in sales performance across stores and assortment categories.
- Build and compare regression models for daily sales prediction.

## Dataset

The project uses the Rossmann Store Sales dataset from Kaggle, consisting of daily sales records, store information, promotional indicators, and calendar variables.

## Tools & Technologies

- Python
- pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn
- Jupyter Notebook

## Methodology

1. **Data Loading & Cleaning:** Loaded the sales and store datasets, inspected data quality, and handled missing competition-distance values.
2. **Feature Engineering:** Created calendar features such as year, month, day, and week of the year.
3. **Exploratory Data Analysis:** Examined sales trends, promotional activity, customer counts, store types, and store-level performance.
4. **Modeling:** Trained Linear Regression and Random Forest Regressor models.
5. **Evaluation:** Compared models using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Key Findings

- Average sales were higher on promotional days than on non-promotional days in the observed data.
- Sales patterns varied across months, weekdays, store types, and assortment categories.
- Store identity and promotion status were among the most influential features in the Random Forest model.

## Model Performance

| Model | MAE | RMSE |
|---|---:|---:|
| Linear Regression | 1,974.80 | 2,625.88 |
| Random Forest Regressor | 1,463.46 | 2,031.77 |

The Random Forest model achieved approximately **25.9% lower MAE** than Linear Regression on the validation dataset.

## Limitations

- The model was evaluated on open-store records from July 2015.
- The observed relationship between promotions and sales does not establish causation.
- This is a learning and portfolio project, not a production forecasting system.

## Conclusion

This project demonstrates an end-to-end retail analytics workflow, from data preparation and exploratory analysis to regression modeling and evaluation. Random Forest outperformed the Linear Regression baseline on the selected validation period.

## Project Files

- `Rossmann_Sales_Analytics_Complete_EDA.ipynb` — notebook containing the analysis and modeling workflow.

## Dataset Source

[Rossmann Store Sales — Kaggle](https://www.kaggle.com/competitions/rossmann-store-sales)
