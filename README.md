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
The dashboard automatically generates a real-time summary based on the selected dataset. Instead of manually writing observations, it calculates key metrics dynamically.

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

# StockSense India V2

So basically after V1 there comes V2 the entire notebook was redesigned into a modular Streamlit app
The notebook code was divided into independent Python modules, each responsible for a specific task:
  1. utils.py handles data loading, validation, and preprocessing.
  2. indicators.py calculates all technical indicators such as Moving Averages, RSI, MACD, ATR, and Bollinger Bands.
  3.  analysis.py applies trading logic to identify trends, breakouts, breakdowns, Golden Cross, Death Cross, and Buy/Sell signals.
  4. charts.py generates interactive Plotly visualizations.
  5. app.py integrates all modules into a user-friendly Streamlit dashboard.

## What is V2 ??

 1. So basically the prev. original notebook performed all calculations and visualizations in a static environment, where the analysis was limited to a single        dataset and required manually executing each cell.
 2. Instead of producing a one-time static analysis, Version 2 allows users to upload any compatible OHLC dataset and instantly generate a complete technical         analysis dashboard with interactive charts, summary metrics, and trading signals. This modular architecture makes the application easier to maintain, extend,     and scale while providing a much more interactive user experience.

## How it works ??

Step 1: Launch the Application
Run the Streamlit application locally or open the deployed web app in your browser.

Step 2: Upload Your Dataset
Click the "Browse Files" button in the sidebar and upload a CSV file containing stock market OHLC data.

Required Columns
Date
Open
High
Low
Close
Volume

Optional Columns
Support
Resistance
Swing High
Swing Low

Step 3: Automatic Data Processing
Once the dataset is uploaded, StockSense India V2 automatically:
Validates the uploaded dataset
Calculates technical indicators (MA20, MA50, RSI, MACD, ATR, Bollinger Bands)
Detects market trends
Identifies Breakouts and Breakdowns
Generates Buy & Sell signals
Computes key market statistics
No manual calculations or configuration are required.

Step 4: Explore the Dashboard
Navigate through the interactive tabs to analyze different aspects of the stock:
1.Price Analysis – Candlestick chart with Moving Averages, Support & Resistance, and Swing Levels.
2.Volume Analysis – Trading volume alongside price movement.
3. Bollinger Bands – Analyze volatility and price position within the bands.
4. RSI, MACD & ATR – Monitor momentum, trend strength, and market volatility.
5. Buy & Sell Signals – Visualize automatically generated trading signals on the price chart.

Step 5: Review the Market Summary
At the top of the dashboard, KPI cards provide a quick overview of:
Current Price
Market Trend
Buy Signals
Sell Signals
Breakouts
Breakdowns
Golden Crosses
Death Crosses

## Demo 
https://github.com/yushh-theanalyst/Stocksense-india/blob/main/scrnrec.mp4


**Successfully deployed the app**:-https://stock-analysis-app-app-wtyn6iyvpkk7jfnacbnlst.streamlit.app/


# StockSense India  V3

An upgrade to the StockSense India dashboard. On top of the existing technical analysis tools (V1) and web app (V2), this version adds a machine learning model that predicts Buy / Hold / Sell signals for NIFTY 50 based on historical price data and technical indicators it is trained all wrapped into Streamlit app.

## Features
* Fetch live NIFTY 50 stock data
* Upload and analyze custom CSV datasets
* Automatic data preprocessing and feature engineering
* ML-based Buy / Hold / Sell prediction
* Model comparison using Logistic Regression, Random Forest, and XGBoost
* Interactive Streamlit dashboard with a responsive UI

## Libraries & Technologies

* Python
* Streamlit
* Pandas
* NumPy
* Plotly
* Scikit-learn
* XGBoost
* yFinance
* Joblib

## What I Learned

* Learned to fetch, clean, and preprocess live stock market data.
* Applied feature engineering using RSI, MACD, Bollinger Bands, ATR, and Moving Averages.
* Compared multiple machine learning models including Logistic Regression, Random Forest, and XGBoost.
* Understood why Precision, Recall, and F1-Score are more reliable than accuracy for imbalanced datasets.
* Learned how class imbalance and feature engineering impact model performance.
* Integrated a trained machine learning model into a Streamlit application with interactive visualizations.

## Project Status
With ML added in, I'm calling this project complete. Started as a spreadsheet, became a web app, and now it's an actual working AI model
