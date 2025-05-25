# DSBA-RECELL-
Supervised Learning Foundations
# ReCell: Predicting Used Device Prices with Linear Regression  
**University of Texas – Data Science & Business Analytics**

This project explores supervised learning foundations through a business case focused on **ReCell**, a company in the used electronics market.  

## 🎯 Objective  
Build an Ordinary Least Squares (OLS) regression model to predict the **normalized used price** of mobile devices based on product features, condition, and brand.

## 📊 Key Highlights
- Achieved **R² = 0.84** on training data and **R² = 0.83** on test data  
- Diagnosed and resolved **multicollinearity** (VIF filtering)  
- Applied **p-value-based feature selection**  
- Validated assumptions of:
  - Linearity
  - Normality of residuals (Shapiro-Wilk, Q-Q plot)
  - Homoscedasticity (Goldfeld-Quandt test)  
- Final model passed all key assumptions with high generalizability

## 🔍 Skills & Tools  
- Python (`statsmodels`, `sklearn`, `matplotlib`, `seaborn`)  
- Feature engineering and variable selection  
- Residual analysis and statistical diagnostics  
- Model evaluation using RMSE, MAE, MAPE, Adjusted R²  

## 📈 Business Takeaway  
The final model helps ReCell **understand the price drivers** for second-hand smartphones, especially highlighting the importance of:
- Original retail price (`normalized_new_price`)
- Camera specs (`main_camera_mp`, `selfie_camera_mp`)
- Time since release (`years_since_release`)

This enables better **pricing strategies and inventory sourcing** in a competitive resale market.

---

📁 *Notebook and results available in this repository.*  
🧠 *Completed as part of the Supervised Learning Foundations module in the DSBA program.*
