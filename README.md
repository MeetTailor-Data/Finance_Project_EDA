# Bank Stocks Finance — EDA

## Project Description
Exploratory Data Analysis on stock price data
of 6 major US banks from January 2006 to January 2016.
The project focuses on analyzing bank performance
during and after the 2007-2008 financial crisis
using real stock market data from Yahoo Finance.

---

## Banks Analyzed
- Bank of America (BAC)
- CitiGroup (C)
- Goldman Sachs (GS)
- JPMorgan Chase (JPM)
- Morgan Stanley (MS)
- Wells Fargo (WFC)

---

## Key Findings
- CitiGroup lost over 95% of its value during 2008 crisis
- All 6 banks are highly correlated — systemic risk confirmed
- Wells Fargo showed strongest post-crisis recovery
- Goldman Sachs maintained highest stock price overall
- 2008 return distributions show extreme volatility
- 30 day moving average confirms sustained downtrend in 2008

---

## Features
- Fetch real stock data using yfinance library
- Multi-level DataFrame with all 6 banks combined
- Daily returns calculation and analysis
- Worst and best single day returns identified
- Rolling 30 day moving average visualization
- Correlation heatmap between all bank stocks
- Clustermap for grouped correlation analysis
- Candlestick chart for technical analysis

---

## Concepts Used

### Pandas
- pd.concat with keys for multi-level DataFrame
- Multi-level indexing and .xs() cross section
- pct_change() for daily returns
- rolling().mean() for moving averages
- loc for date range filtering
- idxmin(), idxmax() for extreme values

### Matplotlib & Seaborn
- Line plots for stock price trends
- histplot with kde for return distributions
- heatmap for correlation analysis
- clustermap for grouped correlations

### Plotly & Cufflinks
- Interactive heatmap with iplot
- Candlestick chart for BAC 2015
- Technical analysis plots

### New Libraries
- yfinance → fetch real stock data from Yahoo Finance
- datetime → set start and end date objects
- pandas_datareader → alternative data source

---

## Project Structure
bank-stocks-finance-eda/
│
├── Finance_Project.ipynb
└── README.md

---

## How To Run

### Requirements
- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn
- yfinance, plotly

### Install
pip install pandas numpy matplotlib seaborn yfinance plotly

### Steps
1. Open Finance_Project.ipynb
2. Run all cells top to bottom
3. Data fetches automatically from Yahoo Finance
4. No CSV file needed

---

## Dataset
- Source: Yahoo Finance via yfinance library
- Period: January 1, 2006 to January 1, 2016
- Stocks: BAC, C, GS, JPM, MS, WFC
- Columns per stock: Open, High, Low, Close, Volume

---

## Author
Meet Tailor
Data Science Learner
GitHub: https://github.com/MeetTailor-Data

---

## License
Created for learning and educational purposes only.
Not financial advice.

---

## Project Status
Completed
Last Updated: May 2026
