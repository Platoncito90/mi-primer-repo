# OptionsGuru · NYSE/NASDAQ Options Analyzer

A browser-based options analysis tool for NYSE and NASDAQ tickers. Enter any US stock symbol, set your parameters, and instantly get a full options chain with Greeks, fair value estimates, and buy signals — no backend required.

## Features

- Real-time options chain for any NYSE/NASDAQ ticker
- Black-Scholes fair value calculation with Edge detection
- Full Greeks: Delta, Gamma, Theta, Vega
- Smart scoring system to identify the best Call and Put opportunities
- Filters by expiration (W1, W2, monthly), moneyness (ITM / ATM / OTM), and type
- Export results to CSV
- Runs entirely in the browser — no installation needed

## How to use

1. Open `options_guru.html` in any modern browser
2. Enter a ticker symbol (e.g. `AAPL`, `NVDA`, `GGAL`)
3. Fill in Spot Price, Historical Volatility, RSI, and Risk-Free Rate
4. Click **Analyze**
5. Browse the options chain, filter by strategy, and export to CSV

## Tech stack

- HTML5 / CSS3 / Vanilla JavaScript
- Black-Scholes model (implemented in JS)
- No external dependencies — fully self-contained

## Screenshots

> *(Add a screenshot of the tool here)*

## Author

**Platoncito90** · [github.com/Platoncito90](https://github.com/Platoncito90)

Built as part of a fintech tools portfolio targeting Argentine and US markets.
