# About

Hello! This is where I store the Jupyter Notebooks from all the Kaggle competitions I've done. If you would like to replicate the results, please download the data from Kaggle.

---

# M5 Forecasting
<b> Rank: top 1% </b>

- Using hierarchical sales data provided by Walmart, the task was to predict sales for the next 28 days for each product.
- The data, covers stores in three US States (California, Texas, and Wisconsin) and includes item level, department, product categories, and store details. In addition, it has explanatory variables such as price, promotions, day of the week, and special events.
- After performing EDA and adding lagged features + features from external data sources, I modeled this as a supervised regression problem using Light GBM. 
- The evaluation metric was calculated using Weighted Root Mean Squared Scaled Error (WRMSSE), a variant of the Mean Absolute Scaled Error with the formula provided by the competition host. 
- My final submission achieved a WMRSSE of 0.56580.