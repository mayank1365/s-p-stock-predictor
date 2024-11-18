# S&P 500 Stock Price Predictor

This project is a machine learning-based **Stock Price Predictor** for S&P 500 stocks. It utilizes historical stock data to forecast future prices, offering insights for investment strategies. By integrating data cleaning, visualization, backtesting, and multi-horizon trend analysis, the model achieves enhanced prediction accuracy.

---

## Features

- **Data Cleaning & Visualization**:  
  - Processed raw stock data to remove inconsistencies.  
  - Visualized key trends and patterns in the stock prices.  

- **Initial Model Training**:  
  - Trained a baseline model with basic parameters for early predictions.  
  - Implemented backtesting to identify prediction errors.  

- **Parameter Enhancement**:  
  - Added advanced parameters:  
    - **Closing Ratio**: The ratio of closing prices over time.  
    - **Multi-Horizon Trends**: Analysis based on past trading days:  
      - **2 Days**: Short-term fluctuations.  
      - **5 Days**: Weekly trends.  
      - **60 Days**: Quarterly patterns.  
      - **250 Days**: Yearly insights.  
      - **1000 Days**: Long-term analysis over 4 years.  

- **Improved Model Training**:  
  - Reduced data size to improve computational efficiency.  
  - Retrained the model with the enhanced parameters.  

- **Backtesting**:  
  - Tested the improved model against historical data.  
  - Achieved higher accuracy and reduced error margins.  

---

## Future Enhancements

To improve the model further, the following directions can be explored:  

- **Global Indices**: Integrate data from Asian and European indices to analyze their influence on S&P 500 pre-market trends.  
- **Macroeconomic Indicators**: Include factors like inflation, GDP growth, and unemployment rates to capture broader market dynamics.  
- **Sector Performance**: Account for trends in key sectors (e.g., tech, healthcare) to refine predictions during sectoral shifts.  
- **Sentiment Analysis**: Use financial news and social media sentiment to predict price movements influenced by public perception.  
- **Real-Time Data**: Incorporate live stock and market data for dynamic and adaptive predictions.  


