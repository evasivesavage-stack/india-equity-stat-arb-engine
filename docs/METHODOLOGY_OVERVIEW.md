# Methodology Overview - Indian Equity Systematic Trading Engine

The engine follows a practical research workflow:

1. Define an Indian equity trading hypothesis.
2. Select liquid instruments.
3. Build a signal and risk framework.
4. Backtest with assumed brokerage/slippage costs.
5. Stress-test cost assumptions.
6. Review session, order-handling, and liquidity constraints.
7. Use forward logs to review real-world costs, spreads, slippage, and broker/API behavior.

India-specific work includes brokerage/tax awareness, circuit-limit risk, order rejection handling, and intraday execution cost review.

The public version intentionally redacts strategy-specific details.
