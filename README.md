# Restaurant Analytics and Recommendation System

## Overview

This project demonstrates an end-to-end machine learning workflow for restaurant analytics using a real-world restaurant dataset.

The repository consists of three machine learning modules:

- Restaurant Rating Prediction
- Restaurant Recommendation System
- Restaurant Cuisine Classification

The project covers data preprocessing, feature engineering, regression, classification, recommendation systems, and model evaluation using Python and Scikit-learn.

---

## Project Modules

### 1. Restaurant Rating Prediction

Objective:
Predict restaurant ratings using machine learning regression models.

Models Used:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Evaluation Metrics:

- Mean Squared Error (MSE)
- R² Score

Result:

- Random Forest achieved the best performance with an R² score of approximately **0.96**.

---

### 2. Restaurant Recommendation System

Objective:

Recommend restaurants based on user preferences.

Features:

- Cuisine Preference
- Budget
- Minimum Rating
- Online Delivery
- Table Booking
- City
- Customer Votes

Techniques Used:

- TF-IDF Vectorization
- Cosine Similarity
- Popularity-based Ranking

---

### 3. Restaurant Cuisine Classification

Objective:

Predict the primary cuisine category of restaurants.

Model Used:

- Random Forest Classifier

Evaluation:

- Accuracy
- Classification Report
- Confusion Matrix

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Repository Structure

```

Restaurant-Analytics-and-Recommendation-ML/

├── data/

├── images/

├── notebooks/

├── README.md

├── requirements.txt

└── .gitignore

```

---

## Results

| Module | Result |
|---------|---------|
| Rating Prediction | Random Forest achieved the best regression performance |
| Recommendation System | Personalized restaurant recommendations using content-based filtering |
| Cuisine Classification | Multiclass cuisine prediction using Random Forest |

---

## Future Improvements

- Hyperparameter tuning
- Streamlit deployment
- Hybrid recommendation system
- Deep learning models
- Real-time restaurant recommendations

---

## Author

**Triveni**


