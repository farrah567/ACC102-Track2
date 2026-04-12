# ACC102 Track2: Tech Stock Volatility Analysis (2024-2025)
**Student Name**: [Ruochen Zhong]
**Student ID**: [2468762]
**Track**: Track2 (GitHub Data Analysis Project)

## 1. Problem & User
This project helps investors understand the risk levels of three major tech stocks: AAPL, AMZN, NVDA. The target users are individual investors and beginner financial learners who need data-driven investment references.

## 2. Data
- Source: WRDS CRSP database
- Access date: April 2026
- Time period: 2024-01-01 to 2025-01-01
- Key fields: date, permno (permanent stock identifier), ret (daily return), prc (closing price)
- Analyzed stocks: AAPL, AMZN, NVDA

## 3. Methods
1. Connect to the WRDS database using Python
2. Download and clean stock data
3. Calculate daily returns and volatility
4. Visualize price trends and volatility using matplotlib

## 4. Key Findings
- NVDA has the highest volatility and the highest investment risk (driven by AI chip industry hype and earnings volatility)
- AAPL is the most stable stock with the lowest volatility (supported by steady consumer electronics sales and cash flow)
- AMZN shows moderate risk and steady growth (volatility tied to e-commerce seasonality and AWS cloud performance)
- All three stocks trended upward in 2024, with NVDA leading in growth rate

## 5. How to Run
1. Install required libraries: wrds, pandas, matplotlib
2. Open the Jupyter Notebook file
3. Run cells one by one
4. Enter your WRDS username and password when prompted
5. View charts and results automatically

## 6. Product Link & Demo
- GitHub Repository: 
- Demo Video: Will be uploaded separately

## 7. Limitations & Next Steps
Limitations:
- Only one year of data is used
- Macroeconomic factors are not included

Next steps:
- Extend the data period to 3-5 years
- Add more stocks and economic indicators
- Use machine learning for price prediction
