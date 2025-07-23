# Titanic Survival Prediction Using Machine Learning

This project uses the classic Titanic dataset to predict whether a passenger survived the Titanic disaster using two machine learning models: **K-Nearest Neighbors (KNN)** and **Decision Tree**.

## Project Features

- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Encoding categorical variables  
- Feature scaling (for KNN)  
- Model training: KNN and Decision Tree  
- Accuracy evaluation and confusion matrix  
- Feature importance analysis  
- Final prediction on test dataset  
- Results interpretation and future insights

## Models Used

| Model           | Accuracy  |
|-----------------|-----------|
| KNN (k=7)       | 82.12%    |
| Decision Tree   | 74.30%    |

## Outcome & Learnings

- **Sex**, **Fare**, and **Pclass** were key features for survival
- KNN gave better performance after tuning and scaling
- Decision Tree helped in understanding **feature importance**
- Clean preprocessing was crucial for both models

## Files

- `titanic-prediction.ipynb` – Jupyter Notebook with complete analysis and code  
- `train.csv` – Training dataset  
- `test.csv` – Unseen test dataset  
- `titanic_submission.csv` – Predictions on test data (optional)  
- `requirements.txt` – List of libraries used

## Future Work

- Try advanced ensemble models like Random Forest or XGBoost  
- Perform hyperparameter optimization (e.g., GridSearchCV)  
- Build a Streamlit or Flask web app for real-time predictions  
- Host the project for portfolio showcase

## Author

Developed by **Azib Malick**  
© 2025 Azib Malick. All rights reserved.
