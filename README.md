# Backtest Solana

An engine for backtesting Solana trading strategies on historical data
from DEXs like Raydium, Orca, and Serum.

## Version 1 planning

We will use sample/fake data so we make our lives easier, not having to index it.

We will blackbox the trading strategy and keep it rudimentary,
possibly a "sell if price drops by more than 10%, buy if price rises by more than 10%" strategy.

The important part of the version 1 is the backtest engine itself.
The part that takes the data and loops over it with the strategy to generate a Profit/Loss (P/L) report.

## Interesting ideas for version 2 (no hard plan)

### Sharpe Ratio

Add Sharpe ratio calculation.

### Add slippage simulation

### Add drawdown analysis

### Use real transactions
