# Market-risk-indicators-on-real-market-data
VaR, Stressed VaR, stress testing and backtesting
Market risk indicators on real market data
VaR, Stressed VaR, stress testing and backtesting

Diptakshi Sen - self-directed project, 2026

Risk factors (Yahoo Finance):
    ^GSPC     S&P 500 index            equity risk
    ^TNX      US 10-year yield (%)     interest rate risk
    HYG       iShares high yield ETF   credit risk
    EURUSD=X  EUR/USD                  FX risk

Method note: equity, credit and FX are PRICE factors, so their risk factor is a
return and the P&L contribution is value x return. Rates are a YIELD factor, so
the risk factor is the CHANGE in yield, and the P&L contribution of a bond
position is -(modified duration) x notional x change in yield. Taking a
percentage change of a yield level would be meaningless.
