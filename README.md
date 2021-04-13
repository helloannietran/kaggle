# About

Hello! This is where I store the Jupyter Notebooks from all the Kaggle competitions I've done. If you would like to replicate the results, please download the data from Kaggle.



# [M5 Forecasting](https://www.kaggle.com/c/m5-forecasting-accuracy)
<b> Rank: top 1% </b><br>
<b> June 30, 2020 </b><br>
[M5 Competition Notebook](https://github.com/helloannietran/kaggle/blob/master/m5-competition-forecasting/m5-forecasting-accuracy.ipynb)

- Using hierarchical sales data provided by Walmart, the task was to predict sales for the next 28 days for each product.
- The data, covers stores in three US States (California, Texas, and Wisconsin) and includes item level, department, product categories, and store details. In addition, it has explanatory variables such as price, promotions, day of the week, and special events.
- I trained on the last 2 years of data, so the full dataset before feature engineering contains 21,797,534 rows and 17 columns.
- After performing EDA and adding lagged features + features from external data sources, I modeled this as a supervised regression problem using Light GBM.
- Since this is a time series, I split the train, validation, and test datasets based on date. Validation and test each contains 28 days of sales for each item.
- The evaluation metric was calculated using Weighted Root Mean Squared Scaled Error (WRMSSE), a variant of the Mean Absolute Scaled Error with the formula provided by the competition host. 
- My final submission achieved a WMRSSE of 0.56580.

For more details on the competition, please follow these links:
- https://mofc.unic.ac.cy/m5-competition/
- https://www.kaggle.com/c/m5-forecasting-accuracy/overview




# [Mechanisms of Action (MoA) Prediction](https://www.kaggle.com/c/lish-moa)
<b> Rank: top 29% </b><br>
<b> November 30, 2020 </b><br>
[MoA Notebook](https://github.com/helloannietran/kaggle/blob/master/mechanisms-of-action-prediction/neural-networks-keras.ipynb)

