# Bitcoin Price Alert System

## Overview

Bitcoin Price Alert System is a Python-based cryptocurrency monitoring tool that tracks Bitcoin prices in real time and sends Telegram notifications when significant price changes occur.

The system periodically retrieves Bitcoin prices from the CoinGecko API and alerts the user whenever the predefined threshold is exceeded.

---

## Features

* Real-time Bitcoin price monitoring
* CoinGecko API integration
* Percentage-based price change detection
* Automatic Telegram notifications
* Local price history storage
* Configurable alert thresholds
* Continuous monitoring mode

---

## Technologies

* Python
* Requests
* JSON
* Telegram Bot API
* CoinGecko API

---

## Project Workflow

1. Retrieve current Bitcoin price from CoinGecko.
2. Compare the current price with the stored threshold.
3. Calculate the percentage change.
4. Send a Telegram alert if the threshold is exceeded.
5. Update the reference price.

---

## Configuration

Users can customize:

* Alert percentage threshold
* Monitoring interval
* Telegram bot settings
* Chat ID

---

## Example Alert

```text
Bitcoin Price Alert

Current Price: $108,500
Previous Price: $103,000
Price Change: +5.3%
```

---

## Project Structure

```text
bitcoin-price/
│
├── main.py
├── threshold.json
├── price_data.txt
└── README.md
```

---

## Applications

* Cryptocurrency monitoring
* Personal investment tracking
* Price alert automation
* Telegram bot integration

---

## Skills Demonstrated

* API Integration
* Automation
* Real-Time Monitoring
* File Handling
* Python Programming
* Notification Systems
* Financial Data Processing

---

## Future Improvements

* Support multiple cryptocurrencies
* SQLite database integration
* Web dashboard
* Historical price visualization
* Docker deployment
* Cloud hosting
* Email notifications

---

## Disclaimer

This project is developed for educational and learning purposes and should not be considered financial advice.
