# sales-advert-prediction
Predict sales using price and advertisement data with linear regression, feature engineering, and model diagnostics in R.
# Sales & Advertisement Predictive Analysis

This project applies linear regression techniques in R to predict sales based on product price and advertisement spending. The project focuses on understanding relationships, building predictive models, and validating them using statistical tests.
 🛠 Methods
- Explored and cleaned structured data (sales, price, advert)
- Built simple linear regression: `sales ~ price`
- Built multiple linear regression: `sales ~ price + advert`
- Visualized data (scatter plots with regression line, residual plots)
- Generated prediction intervals and confidence intervals
- Conducted model diagnostics:
  - **Breusch-Pagan test**: checked for heteroscedasticity
  - **Variance Inflation Factor (VIF)**: checked for multicollinearity
 📈 Results
- Both price and advertisement spending significantly impact sales
- Multiple regression model provided stronger predictive performance
- Diagnostics confirmed model assumptions were met (no heteroscedasticity, no multicollinearity)
💻 Tools
- R (base, `lmtest`, `car`)
- Visualization using base R plotting
📂 Files[Sales and Advertisement Data.xlsx](https://github.com/user-attachments/files/21068468/Sales.and.Advertisement.Data.xlsx)
🚀 How to run
1. Open `analysis.R` in RStudio  
2. Run the full script to generate models, plots, and diagnostics  
[Sales and Advertisement Data.xlsx](https://github.com/user-attachments/files/21068465/Sales.and.Advertisement.Data.xlsx)
 ✉️ About
This was an initial project for applying predictive modeling in class and developing data analytics skills relevant to business and finance.
