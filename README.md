

# Walmart Sales Forecasting

This project involves predicting department-wise weekly sales for Walmart stores using historical data. The dataset includes store information, markdown events, and various economic indicators such as unemployment rates and CPI.

## Dataset
- **Walmart Store Sales** (2010-2012) with 421,570 records.
- **Features**: 
  - Store, Department, Date, Weekly Sales, IsHoliday.
  - Economic indicators like CPI, Unemployment, Fuel Prices, and Markdowns.

## Key Techniques
1. **Exploratory Data Analysis (EDA)**:
   - Analysis of sales trends over time, impact of holidays, and markdown events.
   - Visualized store and department sales patterns.

2. **Data Preprocessing**:
   - Treated missing values in Markdown columns with rolling averages.
   - Created new features like `week`, `year`, and holiday indicators.

3. **Feature Engineering**:
   - Added features for major holidays (Christmas, Thanksgiving, Super Bowl).
   - Generated department-wise sales summaries and applied Box-Cox transformations for normalization.

4. **Modeling**:
   - Various regression models, including Random Forest and Linear Regression, were evaluated.
   - Weighted mean absolute error (WMAE) used as the evaluation metric, with higher penalties for holiday weeks.

## Results
- **Best Model**: Achieved good accuracy by combining time-series analysis with holiday and markdown features.
- **Key Insights**: Significant sales spikes were observed during holidays like Thanksgiving and Christmas.

## Conclusion
This project demonstrates the use of machine learning and time-series analysis to predict Walmart’s weekly sales, highlighting the importance of economic factors and promotional events.

