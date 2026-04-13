# Titanic-Data-Preprocessing

This project focuses on **data cleaning and preprocessing** of the Titanic dataset to prepare it for machine learning tasks.

## What's Included

- `TitanicDataset.csv` – Input dataset  
- `preprocessing.py` – Data cleaning script  
- `cleaned_titanic.csv` – Processed dataset  
- `fare_outliers.png` – Outlier visualization  

## Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- scikit-learn  

## Key Steps

- Handled missing values (Age, Embarked)  
- Encoded categorical features (Sex, Embarked)  
- Applied feature scaling (Age, Fare)  
- Detected and removed outliers  

## How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
python preprocessing.py
