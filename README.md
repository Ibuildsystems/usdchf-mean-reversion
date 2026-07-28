# USDCHF Mean Reversion Model

> Automated statistical mean reversion trading system developed in MQL5 for MetaTrader 5.

**Status:** Live Forward Testing 🟢  
**Language:** MQL5  
**Market:** USDCHF  
**Strategy Type:** Statistical Mean Reversion

---

# Overview

This repository documents the research, development, and validation of an automated USDCHF mean reversion trading strategy.

The objective of the system is to identify statistically favorable reversal opportunities following temporary market dislocations while maintaining disciplined risk management through fully automated execution.

The strategy was developed through an iterative quantitative research process involving historical testing, walk-forward optimization, out-of-sample validation, and live forward testing.

---

# Features

- Fully automated trade execution
- Statistical mean reversion methodology
- Market regime filtering
- ATR-based position sizing
- Automated stop-loss and trade management
- Walk-forward validated
- Portfolio-compatible design

---

# Research Process

Development followed a systematic quantitative research workflow consisting of:

- Historical market analysis
- Statistical hypothesis development
- Parameter optimization
- Walk-forward optimization
- Out-of-sample validation
- Live forward testing
- Continuous strategy refinement

The objective throughout development was to maximize robustness while minimizing parameter sensitivity and overfitting.

---

# Results

## Performance Summary

| Metric | Value |
|---------|------:|
| Historical Period | 2018–2025 |
| History Quality | 99% |
| Total Trades | 241 |
| Profit Factor | 1.97 |
| Recovery Factor | 6.77 |
| Sharpe Ratio | 6.80 |
| Balance Drawdown | 7.86% |
| Equity Drawdown | 8.57% |

---

## Key Findings

- Historical validation completed using approximately seven years of USDCHF market data.
- Historical Profit Factor of **1.97** indicates profitable trades generated nearly twice the gross losses.
- Maximum historical balance drawdown remained below **8%**, demonstrating disciplined risk management.
- Strategy maintained a high historical Sharpe Ratio while controlling portfolio risk.
- Walk-forward optimization was used throughout development to evaluate parameter robustness.
- Designed to complement trend-following systems within a diversified systematic trading portfolio.
- Live forward testing is currently underway.

---

![Equity Curve](Equity%20Curve)

The historical equity curve demonstrates consistent long-term growth while maintaining relatively shallow drawdowns throughout the testing period.

---

## Backtest Statistics


![Performance Metrics](Performance%20Metrics)
---

# Risk Management

Risk management is integrated directly into the execution framework.

Core components include:

- Fixed percentage risk per trade
- Volatility-adjusted position sizing
- Automated stop-loss management
- Dynamic trade management
- Portfolio exposure controls
- Controlled maximum drawdown objectives

The strategy prioritizes long-term capital preservation and consistent execution over maximizing short-term returns.

---

# Technology

- MQL5
- MetaTrader 5
- Quantitative Research
- Statistical Analysis
- Walk-Forward Optimization
- Algorithmic Trading

---

# Future Improvements

Future research includes:

- Expanded Monte Carlo robustness testing
- Additional portfolio optimization
- Adaptive position sizing research
- Enhanced market regime classification
- Continued live performance monitoring

---

# Disclaimer

This repository documents the quantitative research methodology, engineering process, and validation framework behind the project.

The proprietary source code, optimized parameters, and trading logic have been intentionally withheld to protect intellectual property while demonstrating the research and development process behind the strategy.
