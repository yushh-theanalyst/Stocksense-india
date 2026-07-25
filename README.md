# StockSense India V1

An end-to-end stock market analysis project built using **Microsoft Excel**, **Python**, and **Plotly**.

The project begins with raw OHLC stock data, performs technical analysis in Excel, calculates advanced indicators in Python, and visualizes everything through an interactive dashboard.
## Project Workflow

  ## Excel Analysis

   The project starts with raw OHLC (Open, High, Low, Close) stock market data.

   Using Microsoft Excel, the following features were calculated:

   - Swing High
   - Swing Low
   - Support
   - Resistance
   - Breakout
   - Breakdown
   - Trend Detection
   - Daily Return
<p align="center">
  <img src=<img width="1812" height="782" alt="excelss" src="https://github.com/user-attachments/assets/20f93eb3-e934-4104-b450-f5ae4f71231f" />
 width="900"/>
</p>

  ##  Python Analysis

   Python(pandas,numpy) was used to calculate advanced technical indicators.

   - Moving Average 20 (MA20)
   - Moving Average 50 (MA50)
   - Bollinger Bands
   - Relative Strength Index (RSI)
   - Moving Average Convergence Divergence (MACD)
   - Signal Line
   - MACD Histogram
   - Average True Range (ATR)
   - Average Volume

   ## Trading Signals

The project generates Buy and Sell signals using multiple technical indicators.

### Buy Signal

- Breakout Confirmation
- High Volume
- RSI Confirmation
- MACD Confirmation
- Golden Cross

### Sell Signal

- Breakdown Confirmation
- High Volume
- RSI Confirmation
- MACD Confirmation
- Death Cross  

## Dashboard made using plotly

- Interactive Candlestick Chart
- Moving Averages
- Bollinger Bands
- Volume Analysis
- RSI
- MACD
- ATR
- Buy Signals
- Sell Signals
- Support & Resistance
## Technical Indicators Visualization

### Moving Average (MA20 & MA50)

<p align="center">
  <img src=<img width="862" height="600" alt="newplot (1)" src="https://github.com/user-attachments/assets/9cc23187-4421-4579-9d4e-ddf2e3cff074" />
 width="850"/>
</p>


### Bollinger Bands

<p align="center">
  <img src=<img width="862" height="525" alt="newplot (6)" src="https://github.com/user-attachments/assets/d467e718-6ec4-4228-9726-f2115f1ee230" />
 width="850"/>
</p>


### RSI,MACD(HISTOGRAM,SIGNAL LINES),ATR

<p align="center">
  <img src=<img width="1800" height="1200" alt="newplot (7)" src="https://github.com/user-attachments/assets/74c8baf5-7ecf-4135-9dfe-6b1ea4f44444" />
 width="850"/>
</p>


### Volume Analysis

<p align="center">
  <img src=<img width="862" height="525" alt="newplot (5)" src="https://github.com/user-attachments/assets/01898c91-60a9-4a56-8a8d-ac6a4be8f865" />
 width="850"/>
</p>


### Support & Resistance Levels

<p align="center">
  <img src=<img width="862" height="600" alt="newplot (2)" src="https://github.com/user-attachments/assets/d2624cef-021c-4723-adaf-f41321b9a73c" />
 width="850"/>
</p>

### SWING LOW & HIGH
<p align="center">
  <img src=<img width="862" height="600" alt="newplot (3)" src="https://github.com/user-attachments/assets/7bb12b6c-f721-4a38-aaad-6ea6ecab7639" />
  <img src=<img width="862" height="600" alt="newplot (4)" src="https://github.com/user-attachments/assets/d14eb8b7-5d28-478a-820c-9e7e4d2d6d3e" />

 width="900"/>
</p>

### Buy & Sell Signals

<p align="center">
  <img src=<img width="862" height="525" alt="newplot (9)" src="https://github.com/user-attachments/assets/a950007f-888d-4d32-99ac-f2372358821c" />
width="850"/>
</p>  
## Key features
The dashboard automatically generates a real-time summary based on the selected dataset. Instead of manually writing observations, the application calculates key metrics dynamically.

The summary includes:

- Current Market Price
- Current Trend (Uptrend / Downtrend)
- Support Level
- Resistance Level
- Total Buy Signals
- Total Sell Signals
- Total Breakouts
- Total Breakdowns
- Total Golden Crosses
- Total Death Crosses
- Highest & Lowest RSI
- Highest ATR
- Average Trading Volume

Since these metrics are generated dynamically, the dashboard automatically updates whenever a different OHLC dataset is loaded.

## Future Improvements (V2)

- AI Recommendation Engine
- Risk-Reward Calculator
- Stop Loss Prediction
- Portfolio Tracker
- Streamlit
- Multi-Stock Comparison
