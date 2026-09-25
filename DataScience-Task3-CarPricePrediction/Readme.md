# Car Price Prediction with Machine Learning

**OASIS INFOBYTE — Data Science Internship | Task 3**

## Objective
Build a regression model that predicts the selling price of a used car based on features such as brand, age, mileage, fuel type, and transmission.

## Tech Stack
- Python 3
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

## Dataset
**Vehicle Dataset from CarDekho** (Kaggle – `nehalbirla/vehicle-dataset-from-cardekho`)

| Column | Description |
|--------|-------------|
| Car_Name | Name / model of the car |
| Year | Year of purchase |
| Selling_Price | Target — selling price (lakhs INR) |
| Present_Price | Current ex-showroom price (lakhs INR) |
| Kms_Driven | Distance driven (km) |
| Fuel_Type | Petrol / Diesel / CNG |
| Seller_Type | Dealer / Individual |
| Transmission | Manual / Automatic |
| Owner | Number of previous owners |

## Project Workflow
1. **Data Cleaning** – null check, duplicate removal, categorical standardisation
2. **Feature Engineering** – `Car_Age` from Year, `Brand` extracted from Car_Name
3. **EDA** – price distribution, fuel-type boxplots, price vs car age scatter
4. **Encoding** – Label Encoding for categorical variables
5. **Correlation Heatmap** – identify key predictors
6. **Train/Test Split** – 80/20
7. **Models Trained**
   - Linear Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
8. **Evaluation** – MAE, RMSE, R²
9. **Feature Importance** – coefficient/importance chart
10. **Predicted vs Actual** – scatter plot validation

## Results

| Model | MAE | RMSE | R² |
|-------|-----|------|----|
| Linear Regression | 1.540 | 2.583 | 0.7411 |
| Random Forest | 1.302 | 3.173 | 0.6093 |
| Gradient Boosting | 1.196 | 2.707 | 0.7158 |

**Best Model:** Linear Regression (R² = 0.7411)

## Key Insights
- **Present_Price** is the dominant predictor of selling price.
- **Car_Age**, **Fuel_Type**, and **Transmission** contribute meaningfully.
- Older cars sell for less; diesel cars command higher prices.
- Automatic and dealer-sold cars tend to have higher prices.

## Files
- `Car_Price_Prediction_ML.ipynb` — Complete commented notebook
- `Car_Price_Prediction_ML.html` — Static HTML export
- `car_data.csv` — Dataset used

---
**Author:** Mina Fatima
**Track:** Data Science
**Task:** Task 3 — Car Price Prediction with Machine Learning
