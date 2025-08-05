# 📊 TradingView Scripts

A collection of custom indicators and strategies written in Pine Script for use in [TradingView](https://www.tradingview.com/). This repository serves as a personal portfolio and toolbox for various market analysis tools.

---

## 📁 Included Scripts

### `macd-divergence.pine`
A clean and enhanced MACD indicator for TradingView that highlights key momentum shifts using visual markers.
- Plots the traditional MACD line, Signal line, and Histogram.
- Encircles MACD crossovers:
 - 🟢 Bullish crossover – MACD line crosses above the Signal line.
 - 🔴 Bearish crossover – MACD line crosses below the Signal line.
- Circle markers appear at crossover points for better visual clarity.
- Color-coded histogram bars indicate momentum strength and direction.
- Includes built-in alert conditions for both crossover and histogram state changes.

```bash
# File: macd-divergence.pine
# Highlights: MACD/Signal line crossovers with circle markers
# Signals: 
#   - Bullish: MACD > Signal
#   - Bearish: MACD < Signal
# Features: Visual markers, color-coded histogram, customizable MA types
```

### `rsi-bb.pine`

