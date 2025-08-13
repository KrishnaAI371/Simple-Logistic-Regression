# Simple Linear Regression: Height vs Weight

This project demonstrates how to use **Simple Linear Regression** in Python with scikit-learn to predict height from weight.  
It includes data preprocessing, model training, evaluation, and residual analysis.

---

## 📂 Dataset
File: `Height-Weight.csv`  
**Columns:**
- `Weight` (kg)
- `Height` (cm)

Example:
| Weight | Height |
|--------|--------|
| 45     | 120    |
| 58     | 135    |
| 70     | 160    |

---

## 🛠 Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 📌 Steps Performed
1. **Load & explore data**  
2. **Visualize Weight vs Height** (scatter plot)  
3. **Split dataset** into training & testing sets  
4. **Standardize features** using `StandardScaler`  
5. **Train** a `LinearRegression` model  
6. **Evaluate** model performance with:
   - MSE, MAE, RMSE
   - R² and Adjusted R²  
7. **Predict** height for a given weight  
8. **Analyze residuals** with KDE and scatter plots

---

## 📊 Results
- **Slope:** 17.03  
- **Intercept:** 157.5  
- **MSE:** 109.78  
- **MAE:** 9.82  
- **RMSE:** 10.47  
- **R² Score:** 0.777  
- **Adjusted R²:** 0.703  
- Predicted height for **80kg**: ~163.01 cm

---

## 🚀 How to Run
1. Clone or download this repository  
2. Install dependencies:
   ``

