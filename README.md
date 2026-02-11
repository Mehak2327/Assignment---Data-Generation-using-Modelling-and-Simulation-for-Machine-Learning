# Data Generation using Modelling and Simulation for Machine Learning

## Objective
To generate synthetic datasets using simulation, train multiple machine learning models, and compare their performance.

---

## Tool Used
Scikit-learn (make_regression)

---

## Methodology

1. Defined parameter ranges:
   - Samples: 100–2000
   - Features: 5–50
   - Noise: 0–50

2. Generated 1000 synthetic datasets using random parameters.

3. Selected one dataset for ML training.

4. Applied data scaling and train-test split.

5. Trained 8 machine learning models.

6. Evaluated models using:
   - RMSE
   - R² Score

---

## Models Used
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- Support Vector Regression  
- KNN  

---

## Results

Model performance comparison table and bar chart are included in the notebook.

The model with lowest RMSE is considered best.

---

## Conclusion

Simulation-based data generation is effective for creating large ML-ready datasets. Ensemble models such as Random Forest and Gradient Boosting generally provide better performance.

---

## How to Run
Open the notebook in Google Colab and run all cells sequentially.
