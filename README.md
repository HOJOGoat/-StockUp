StockUp

A command-line stock analysis tool that delivers comprehensive financial and technical insights, plus an AI-driven recommendation with a confidence score.

1.) Features

a) Fundamental Metrics: P/E, P/B, EV/EBITDA, ROE, ROA, Net Margin, Debt/Equity, CAGR

b) Technical Indicators: RSI, SMA/EMA, MACD, Bollinger Bands, ATR, OBV, VWAP

c) Charts: Automatically generates RSI & SMA plots in charts/

d) News Sentiment: Scores the latest 10 headlines using VADER

e) AI Recommendation: Buy/Hold/Sell signal with confidence percentage

2.) Installation

I) Clone or download the repository:

git clone https://github.com/HOJOGoat/StockUp.git
cd StockUp


II) Install dependencies:

pip install --upgrade pip
pip install -r requirements.txt

3.) Usage

Run the analysis script with a stock ticker symbol:

python ppa.py <TICKER>

Example:

python ppa.py AAPL

Results will appear in the console, and chart images will be saved under the same directory.

4.) License

MIT © 2025 HOJOGoat
