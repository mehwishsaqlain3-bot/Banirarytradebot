# Forex Trading Bot

An advanced automated Forex trading bot designed for real-time currency pair analysis and intelligent buy/sell signals with risk management.

## 🎯 Features

- **Automated Trading Strategies**: Intelligent algorithms for EUR/USD, GBP/USD, and 20+ currency pairs
- **Real-time Market Analysis**: Live price feeds and technical indicator calculations
- **Buy/Sell Signal Generation**: Accurate signals based on multiple indicators
- **Risk Management**: Automatic stop loss and take profit placement
- **Backtesting Engine**: Test strategies on historical data before live trading
- **Easy Configuration**: Simple JSON-based setup for custom parameters
- **Multi-Timeframe Analysis**: Support for M1, M5, M15, H1, H4, D1 timeframes
- **Performance Tracking**: Real-time P&L monitoring and trade history
- **Alert System**: Email and SMS notifications for trade signals

## 📊 Technical Indicators

- Moving Averages (SMA, EMA)
- RSI (Relative Strength Index)
- MACD (Moving Average Convergence Divergence)
- Bollinger Bands
- Stochastic Oscillator
- ADX (Average Directional Index)

## 💻 Supported Platforms

- MetaTrader 4 (MT4)
- MetaTrader 5 (MT5)
- Oanda API
- Interactive Brokers
- Alpaca Trading

## 🚀 How to Install

1. Clone the repository:
```bash
git clone https://github.com/mehwishsaqlain3-bot/Banirarytradebot.git
cd Banirarytradebot
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Configure your broker credentials in `config.json`:
```json
{
  "broker": "mt5",
  "account": "your_account_number",
  "password": "your_password",
  "server": "your_broker_server"
}
```

4. Run the bot:
```bash
python forex_bot.py
```

## ⚙️ Configuration

Edit `config.json` to customize:
- Trading pairs
- Timeframe
- Risk percentage per trade
- Stop loss and take profit levels
- Indicator parameters
- Trading hours

Example configuration:
```json
{
  "pairs": ["EURUSD", "GBPUSD", "AUDUSD"],
  "timeframe": "M5",
  "risk_percent": 2,
  "stop_loss_pips": 50,
  "take_profit_pips": 100,
  "max_trades": 3
}
```

## 📈 Backtesting

Test your strategy on historical data:
```bash
python backtest.py --pair EURUSD --timeframe H1 --period 6months
```

## 📋 Requirements

- Python 3.8+
- MetaTrader 4/5 or Broker API
- pandas, numpy, TA-Lib
- requests, websocket-client

See `requirements.txt` for full dependencies.

## 🔒 Security

- Keep your broker credentials in `.env` file (never commit to git)
- Use API keys with limited permissions
- Enable 2FA on your broker account
- Monitor trading activity regularly

## 📊 Performance Metrics

The bot tracks:
- Total trades
- Win rate percentage
- Average profit per trade
- Maximum drawdown
- Sharpe ratio
- ROI (Return on Investment)

## 🛑 Important Disclaimer

⚠️ **TRADING RISK WARNING**

- **Forex trading involves substantial risk of loss.** Past performance does not guarantee future results.
- **This bot is provided as-is without any warranty.** Use at your own risk.
- **You may lose more than your initial investment.** Start with small amounts.
- **No bot can guarantee profits.** Market conditions are unpredictable.
- **Use proper risk management** - never risk more than 2-3% per trade.
- **This is not financial advice.** Consult with a financial advisor before trading.
- **Test thoroughly** on a demo account before using real money.
- **Legal compliance**: Binary and Forex trading is regulated differently in various countries. Check your local regulations.

## 📞 Support & Contact

For issues, feature requests, or support:
- GitHub Issues: [Create an issue](https://github.com/mehwishsaqlain3-bot/Banirarytradebot/issues)
- Email: your_email@example.com

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Contributing

Contributions are welcome! Please fork the repository and submit pull requests.

---

**Last Updated**: 2026-07-11  
**Version**: 2.0
