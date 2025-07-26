# freqtrade_hyperliquid_download-data

This repository contains **downloaded market data** for the [Hyperliquid](https://hyperliquid.xyz) decentralized exchange, formatted and ready to be used with [Freqtrade](https://www.freqtrade.io).

It will progressively grow over the months.   
**Includes:** All supported trading pairs and markets on Hyperliquid, meaning spot AND futures

**Check what's inside** 
- [latest data_content_futures.txt](./data_content_futures.txt) for details.
- [latest data_content_spot.txt](./data_content_spot.txt) for details.


---

## What’s Inside

- Historical OHLCV data from Hyperliquid
- Market pairs compatible with Freqtrade
- Data files organized by trading pair and time interval (e.g., `1m`, `5m`, etc.)
- Automatically updated via GitHub Actions

---

## Usage with Freqtrade

This repository is meant to serve as the `--datadir` when running Freqtrade backtesting or hyperparameter optimization.

### Setup

1. **Clone this repository**:
   ```bash
   git clone https://github.com/frequenthippoOrg/freqtrade_hyperliquid_download-data.git
2. **Update this repository**:
   git fetch origin
   git reset --hard origin/main


# If you want to fork it, you'll have to activate the workflows on your GitHub repo yourself, otherwise you are on a dead end !