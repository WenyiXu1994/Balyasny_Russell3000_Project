# Balyasny_Stock_Price_Prediction_Project
This is an internship project finished with Balyasny Asset Management. No confidential information is included.  

The goal is to build a model to predict short-term stock price movements in the consumer discretionary of the Russell3000 index.
  
All the historical price and volumn data used in the "Simple_indicator_formation.ipynb" file is uploaded to Google Cloud. You can access them through https://drive.google.com/drive/folders/1iU9uRVFZ1Koh8b436gbxqzAUjdcH1AG_?usp=sharing

## Project Description

### Step 1: Calculate simple indicators and 2-way & 3-way complex indicators.
Simple indicators: Formed from commonly used trading rules.
2-way & 3-way complex indicators: Formed by combining simple indicators.  
![avatar](/images/rules.png)

### Step 2：Identify big recession periods
Used historical S&P index data and VIX index data to identify recession periods.  
VIX index reflexes the volatility of the financial market.  
Recessions usually come with a low S&P index and high VIX index.  
![avatar](/images/recession.png)

### Step 3: Build predictive models on a rolling basis.
Built a random forest model and optimized its hyper-parameters by cross-validation on a rolling basis.
![avatar](/images/rolling.png)

## Results
Out model increaes the prediction accuracy by 9%.  
The backtesting results of one example company that proves the superiority of our model is shown below.  
![avatar](/images/backtest.png)
