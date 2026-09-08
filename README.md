# Car Price Prediction

> Predict the selling price of used cars from features like year, kilometers driven, fuel type, and transmission.

## Dataset
CarDekho used-car listings — **301 records, 9 features**
Source: `car_data.csv`

## Features Used
- Year, Present Price, Kilometres Driven
- Fuel Type, Seller Type, Transmission, Owner History

## Models & Results

| Model | MAE | RMSE | R² |
|---|---|---|---|
| Linear Regression | 1.47 | 2.52 | **0.753** |
| Gradient Boosting | 1.17 | 2.63 | 0.732 |
| Random Forest | 1.47 | 3.52 | 0.520 |

**Best model: Linear Regression** — highest R² (0.753) on the test set.

## Pipeline
1. Data cleaning & deduplication
2. Feature encoding (Label Encoding for categoricals)
3. Train/test split (80/20)
4. Model training & comparison
5. Feature importance visualization

## Tech Stack
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn

## Author
[Abdul Rafay](https://abdul-rafay-1942.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/abdul-rafay-04397332a) · [Kaggle](https://www.kaggle.com/abdulrafay1942)
