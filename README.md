 # Real-Time-Cryptocurrency-Insights-Email-Automation

A Python-based tool that fetches real-time cryptocurrency data from CoinGecko, identifies the Top 10 Cryptos to Sell and Bottom 10 Cryptos to Buy, saves the results in a CSV file, and sends a daily email report—automatically every day at 8:00 AM.

## 🚀 Features

✅ Real-time Crypto Prices via CoinGecko API

📊 Top & Bottom 10 Analysis based on 24h price change

📥 Saves Data as CSV with timestamp

📧 Automated Email Report with attached CSV file

⏰ Scheduled to Run Daily at 8:00 AM

🔐 Ethical API usage with error handling and reporting

## 🔧 Tech Stack

Tool	-Purpose
Python	-Core programming
Requests	-API integration
Pandas	-Data handling & analysis
Schedule-	Automating daily tasks
smtplib, email	-Email composition & sending
CoinGecko API	Live cryptocurrency market data

## 📂 CSV Output Structure
The exported CSV file contains:

id (crypto name)
current_price
market_cap
price_change_percentage_24h
high_24h, low_24h
ath (all-time high)
atl (all-time low)
time_stamp (date & time of extraction)

