# 🏠 California Housing Regression Analysis 📊

Welcome to the California Housing Regression project! This notebook explores and compares a variety of regression models to predict median house values in California using the California Housing Dataset. The focus is on clear insights, beautiful visualizations, and well-commented, modular code.

---

## 📂 Project Structure

- ✅ Data Preprocessing
- 📈 Linear Regression
- 📐 Polynomial Regression
- 🔵 Ridge, Lasso, ElasticNet
- 🌳 Decision Tree Regression
- 🌲 Random Forest Regression
- 🔥 Gradient Boosting Regression (optional)
- 📊 Visualizations: Predictions, Residuals, Feature Importances

---

## 🧠 Models Implemented

| Model                  | Description                                                        |
|------------------------|--------------------------------------------------------------------|
| Linear Regression      | Simple baseline model that fits a straight line                    |
| Polynomial Regression  | Captures non-linear patterns by transforming features              |
| Ridge Regression       | L2 regularization to reduce overfitting                            |
| Lasso Regression       | L1 regularization for feature selection                            |
| ElasticNet Regression  | Combination of L1 and L2 regularization                            |
| Decision Tree          | Tree-based model to capture splits and non-linearity               |
| Random Forest          | Ensemble of trees to reduce overfitting and improve accuracy       |
| Gradient Boosting 🔥   | (Optional) Boosted ensemble for top-tier predictive performance     |

---

## 🗃️ Dataset

The dataset used is the 📦 California Housing Dataset from `sklearn.datasets.fetch_california_housing`. It includes:

- 📍 Location-based features (Latitude, Longitude)
- 🧍 Population, Households, Median Income
- 🏡 Housing Age, Rooms per Household
- 🎯 Target: Median House Value

---

## 📊 Visualizations

Every model section includes:

- ✅ Actual vs. Predicted Plot
- 📉 Residual Distribution
- 🧮 Feature Importance (if available)

All plots are styled using Seaborn and Matplotlib with clear titles and labeled axes.

---

## 🚀 How to Run

1. Open the notebook in Google Colab or JupyterLab.
2. Ensure the files:
   - california_processed.csv
   - california_target.csv
   are available in the same directory.
3. Run the notebook section-by-section to train and evaluate each model.

---

## 🧰 Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
