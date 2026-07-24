# Used Car Price Prediction Dataset

## Dataset Overview

This project performs Exploratory Data Analysis (EDA), Data Cleaning, and Feature Engineering on a Used Car Price Prediction dataset. The objective is to prepare the dataset for future Machine Learning models.

---

## Dataset Information

- Total Records: 4009
- Total Features: 12

---

## Data Quality Issues Identified

- Missing values in fuel_type, accident, and clean_title.
- Invalid fuel type values such as "-" and "not supported".
- Price and mileage stored as text instead of numeric values.
- Presence of price outliers representing luxury vehicles.

---

## Cleaning Techniques Applied

- Converted price into numeric format.
- Converted mileage into numeric format.
- Replaced invalid fuel type values with missing values.
- Filled missing categorical values using the mode.
- Verified that no duplicate records existed.

---

## Feature Engineering

The following features were created:

- car_age
- mileage_per_year
- price_per_mile
- has_accident
- is_automatic

---

## Five Key Insights

1. Gasoline is the dominant fuel type.
2. No duplicate records were found.
3. Missing values were successfully handled.
4. Luxury vehicles contribute to price outliers.
5. Vehicle age and mileage are important factors affecting price.

---

## Output

- task-3.ipynb
- cleaned_used_cars.csv
