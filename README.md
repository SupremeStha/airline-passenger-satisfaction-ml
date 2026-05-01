# Airline Passenger Satisfaction Prediction

Predicting airline passenger satisfaction using ensemble ML methods 
on 129,888 passenger records.

## Results
| Model | Accuracy | F1-Score | ROC-AUC |
|---|---|---|---|
| Random Forest | 93.5% | 0.935 | 0.985 |
| LightGBM | 91.9% | 0.920 | 0.974 |
| Logistic Regression | 87.2% | 0.872 | 0.930 |

## Key Findings
- Online Boarding and In-flight Wi-Fi are the strongest 
  predictors of passenger satisfaction
- Ensemble methods significantly outperform linear baseline
- Service quality matters more than operational delays

## Pipeline
Data Cleaning → EDA → Feature Engineering → 
SMOTE → Model Training → Evaluation

## Tech Stack
Python, scikit-learn, LightGBM, Pandas, NumPy, Matplotlib, Seaborn

## Dataset
[Airline Passenger Satisfaction – Kaggle](link here)
