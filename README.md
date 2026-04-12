ACC102 Track2 - Tech Stock Volatility Analysis 

1.Problem & User
This project addresses the need for investors to understand the risk levels of major tech stocks (GOOGL, AMZN, META) by analyzing price trends and volatility; the target users are risk-aware individual investors and beginner financial analysts. 


2.Data 
a.Source: WRDS CRSP (Center for Research in Security Prices) database, the authoritative financial data source for academic research. 
b.Access date: April 2026 
c.Key fields: Trading date (date), permanent stock identifier (permno), daily return (ret), closing price (prc). 

3.Methods 
a.Connect to WRDS and retrieve data using SQL queries.
b.Clean data with pandas (date conversion, remove missing values, correct negative   prices).
c.Calculate returns and volatility (standard deviation).
d.Visualize trends and volatility comparison using matplotlib.


4.Key Findings
a.META exhibits the highest volatility (standard deviation of daily returns), indicating the highest investment risk among the three stocks. 
b.GOOGL shows the lowest volatility and the most stable price trend, making it a suitable choice for risk-averse investors. 
c.AMZN has moderate volatility with steady price growth, balancing risk and potential returns. 
d.All three tech stocks saw an overall upward price trend in 2024, reflecting the positive performance of the tech sector. 
f.The volatility gap between META and GOOGL is about 0.02 (standard deviation), highlighting significant risk differences in the tech stock market. 


5.How to run
a.Ensure the wrds, pandas, and matplotlib libraries are installed (run pip install wrds pandas matplotlib in the terminal). 
b.Open the Jupyter Notebook file (ACC102-Track2.ipynb) 
c.Run the notebook cells sequentially: enter WRDS account credentials when prompted, then the code will automatically fetch data, clean it, and generate visualizations. 
d.All output (data results, charts) will be displayed directly in the notebook. 


6.Product link / Demo 
GitHub Repository:  https://github.com/farrah567/ACC102-Track2
Demo Video:  


7.Limitations & next steps 
?Limitations: The analysis only covers a 1-year period (2024), which may not reflect long-term stock performance; macroeconomic factors (e.g., interest rate changes) are not incorporated into the analysis.
?Next steps: Extend the data period to 5 years for long-term trend analysis; add macroeconomic indicators (e.g., GDP growth, inflation) to explore their impact on stock volatility; use machine learning models (e.g., LSTM) to predict future stock prices and risk levels.

