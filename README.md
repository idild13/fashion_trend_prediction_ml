# Predicting Fashion Trends with Machine Learning 👗🧠

## Project Overview 
This project explores whether short-term fashion trends can be predicted using historical trend data. Using supervised machine learning, I trained and evaluated classification models to forecast whether a fashion item will become a future trend based on past popularity signals.

The goal of the project is not only model performance, but also to demonstrate an end-to-end data science workflow: data exploration, feature engineering, model training, evaluation, and interpretation.

---

## Dataset
The dataset contains historical fashion trend signals over time, including indicators such as trend intensity and temporal patterns. Each observation represents a fashion item at a given point in time, with a binary target variable indicating whether it becomes a future trend.

Key steps:

- Loaded and inspected the raw dataset (tendances.csv)
- Checked for missing values and inconsistencies
- Selected relevant numerical features for modeling
- Defined a clear target variable for prediction

---
## Project Structure
```text
fashion_trend_prediction_ml/
├── notebooks/
│   └── fashion_trend_prediction_ml.ipynb
├── LICENSE
├── README.md
└── requirements.txt
```
---
## Methodology

### 1. Exploratory Data Analysis (EDA)

- Analyzed feature distributions and class balance
- Identified correlations between trend indicators
- Validated assumptions before modeling

### 2. Data Preparation

- Split data into training and test sets
- Scaled numerical features where appropriate
- Ensured reproducibility using fixed random states

### 3. Modeling

I implemented and compared multiple classification models:

- Logistic Regression (baseline)
- Random Forest Classifier

These models were chosen to balance interpretability and performance.

### 4. Evaluation

Model performance was evaluated using:

- Accuracy
- Precision, Recall, and F1-score
- Confusion matrices

This allowed for a nuanced comparison beyond a single metric, especially given potential class imbalance.

---

## Results & Insights

- Tree-based models captured non-linear relationships better than linear baselines
- Certain trend intensity features showed stronger predictive power
- The results suggest that short-term trend momentum can be partially predictive, but with clear limitations

This highlights both the potential and the uncertainty inherent in forecasting fashion trends.

--- 

## Limitations & Next Steps

- Dataset size and feature richness limit generalization
- External signals (social media, search trends, seasonality) could significantly improve predictions
- Future iterations could explore time-series models or ensemble approaches

--- 

## Tech Stack

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

### 👉 [View notebook here](https://github.com/idild13/fashion_trend_prediction_ml/blob/main/notebooks/fashion_trend_prediction_ml.ipynb)

---

## 👩‍💻 Author
**Idil Dorak**  
Data & Marketing Analytics Professional  
📍 Berlin | [Le Wagon Bootcamp Graduate]
