# Quantitative Live Trading System

This repository showcases a **live trading system** developed for factor-based quantitative strategies using high-frequency(tick_level and minute-level) and daily data.
- **simulation parameter:**
- **Transaction cost:** **0.05%** commission fee
- **Exclude:** **ST stocks**, **illiquid stocks**, and stocks hitting **limit up/down**
- **Execute trades** using the **30-minute VWAP** from market open

**Note**: This repository contains proprietary trading strategies and is for demonstration purposes only. Sorry for keeping it secret.
**Contact**: For collaboration or detailed inquiries, please reach out to **qtx2711135576@gmail.com**

## Overview
- **Data**: ~100 neutralized factors from minute-level and daily-level datasets.  
- **Modeling**:  
  - Traditional linear models  
  - Modified Boosting Model and deep learning models for factor combinations  
  - End-to-end temporal deep learning for price-volume factors  
- **Additional Signal Generation**:
  - Multi-source signals derived from time-series analysis and large language models applied to unstructured data, including financial news and broker analyst forecasts
- **Portfolio Construction**:  
  - Signals and factor combination outputs feed into a portfolio optimizer  
  - Daily/Weekly trading positions generated accordingly  

## Trading Execution
- Rebalancing occurs within the first **30 minutes after market open**  
- Positions updated in batches to manage risk and liquidity  

## Purpose
The project demonstrates the ability to:  
- Handle high-dimensional factor datasets  
- Combine multiple predictive models  
- Generate and integrate multi-source signals  
- Optimize and execute daily trading strategies

