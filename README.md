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
  <img src=excelss.png/>
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
  <img src=ma20ma50.png/>
</p>


### Bollinger Bands

<p align="center">
  <img src=bbbands.png/>
</p>


### RSI,MACD(HISTOGRAM,SIGNAL LINES),ATR

<p align="center">
<img src=macdrsiatr.png/>
</p>


### Volume Analysis

<p align="center">
  <img src=vol.png/>
</p>


### Support & Resistance Levels

<p align="center">
<img src=suppresist.png/>
</p>

### SWING LOW & HIGH
<p align="center">
 <img src=swinghi.png/>
  <img src=swinglo.png/>
</p>

### Buy & Sell Signals

<p align="center">
<img src=sellbuysig.png/>
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
<p align="center">
<img src=ss.png/>
</p>  
 
## kaggle notebook is uploaded for further info

## Future Improvements (V2)

- AI Recommendation Engine
- Risk-Reward Calculator
- Stop Loss Prediction
- Portfolio Tracker
- Streamlit
- Multi-Stock Comparison
