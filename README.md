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
An enhanced RSI indicator with optional Bollinger Bands and color-coded signal logic to help identify momentum and potential reversal zones.
- Plots a custom RSI with dynamic coloring:
 - 🔴 Red when RSI is below 50 (bearish momentum)
 - 🔵 Blue when RSI is above 50 (bullish momentum)
- Includes optional Bollinger Bands (based on SMA-50) over the RSI line to identify volatility and overbought/oversold ranges.
- Visual gradient fills highlight overbought (above 70) and oversold (below 30) zones.
- Optional divergence detection between price and RSI:
 - ✅ Bullish Divergence: Price makes a lower low while RSI makes a higher low
 - ❌ Bearish Divergence: Price makes a higher high while RSI makes a lower high
- Alert conditions provided for both divergence types.

```bash
# File: rsi-bb.pine
# Highlights:
#   - RSI color changes based on 50 threshold (Red < 50, Blue > 50)
#   - Optional smoothing and Bollinger Bands
#   - Built-in divergence detection and alerts
# Visuals:
#   - Gradient fill for overbought/oversold
#   - Dynamic MA and BB overlays (configurable)
```
