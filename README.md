# Patient Churn Prediction using Random Forest

This project aims to predict patient churn (attrition) using a synthetic healthcare dataset. By analyzing patient demographics, satisfaction scores, and billing history, we developed a Random Forest model to identify high-risk patients.

## Project Overview
- **Goal:** Predict if a patient will stop using healthcare services (`Churn`).
- **Data:** 500 patient records with 11 features including `Age`, `Satisfaction_Score`, and `Total_Bill_Amount`.
- **Model:** Random Forest Classifier optimized via `GridSearchCV`.
- **Performance:** Achieved ~**74% accuracy** on the test set.

## Key Insights
- **Feature Importance:** The model identified billing amounts and satisfaction scores as primary drivers of churn.
- **Partial Dependence:** Analysis shows how variables like `Age` and `Satisfaction_Score` specifically influence the probability of churn.

[View Presentation](https://ratraverfallick.github.io/portfolio/slides/Patient-Churn-Prediction.pdf)

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/patient-churn-prediction.git](https://github.com/YOUR_USERNAME/patient-churn-prediction.git)

