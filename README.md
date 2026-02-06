# Quantitative Live Trading System

This repository showcases a **live trading system** developed for factor-based quantitative strategies using high-frequency and daily data.

## Overview
- **Data**: ~100 factors from minute-level and daily-level datasets (Level 2 data).  
- **Modeling**:  
  - Traditional linear models  
  - XGBoost  
  - Deep learning models for factor combinations  
  - End-to-end temporal deep learning for price-volume factors  
- **Signal Generation**:  
  - Multi-source signals from time series analysis and large language models  
  - Each stock assigned **long, short, or neutral** signals daily  
- **Portfolio Construction**:  
  - Signals and factor combination outputs feed into a portfolio optimizer  
  - Daily trading positions generated accordingly  

## Trading Execution
- Rebalancing occurs within the first **15 minutes after market open**  
- Positions updated in batches to manage risk and liquidity  

## Purpose
The project demonstrates the ability to:  
- Handle high-dimensional factor datasets  
- Combine multiple predictive models  
- Generate and integrate multi-source signals  
- Optimize and execute daily trading strategies
