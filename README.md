# Support-and-Resistance-Indicator
Simple TradingView Pinescript indicator for support and resistances

## Visuals
- **Support Lines**  
  - Color: Lime  
  - Drawn at each detected pivot low  
  - Extended to the right across the chart
- **Resistance Lines**  
  - Color: Red  
  - Drawn at each detected pivot high  
  - Extended to the right across the chart

## Usage Notes
- Works on any symbol and timeframe (Higher Timeframes have Higher Precedence) supported by TradingView.
- Larger `leftBars` / `rightBars` values filter out noise and keep only major swing levels. Smaller values react faster but can produce more lines.
- This is an **indicator**, not a strategy. It does not enter or exit trades by
  itself. Combine with your own entry logic (RSI, trend filters, SMT, etc.).
- Lines are derived purely from historical price action; they do not guarantee future support or resistance.

## WARNINGS
ANY LEVELS, ENTRIES/EXITS ARE NOT FINANCIAL ADVICE. ALWAYS USE MULTIPLE CONFLUENCES AND DONT ENTER BLINDLY BASED OFF THIS INDICATOR. THIS IS NOT FINANCIAL ADVICE.

# License & Credits
This Pine Script® code is subject to the terms of the Mozilla Public License 2.0:
https://mozilla.org/MPL/2.0/

Copyright © PlasmaZero