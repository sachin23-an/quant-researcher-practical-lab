Lab 1 — Foundations (stationarity, look-ahead bias, walk-forward) → Alpha Research Loop → Momentum + IC/IR → Cointegration/pairs trading → honest backtest engine with costs → Complexity Trap

Lab 2 — Regime classification: logistic regression from scratch (gradient descent), decision tree → gradient boosting → XGBoost, proper evaluation (precision/recall/AUC, not just accuracy), walk-forward + 4-point leakage audit.

Lab 3 — Options/VaR: Black-Scholes + Greeks (cross-checked against finite-difference), binomial pricing (European vs American early-exercise), all 4 VaR methods side-by-side, CVaR, Kupiec backtest, stress scenarios.

Lab 4 — Microstructure/execution: simulated order book, Roll's spread estimator (recovers spread from price changes alone, no quote data), VWAP/TWAP scheduling, Almgren-Chriss market impact, PCA factor risk decomposition, Kelly + risk budgeting.

Lab 5 — The advanced stuff: ARIMA forecasting, a from-scratch Deflated Sharpe demo (100 random no-edge strategies, shows how "luck" alone produces a fake 95th-percentile Sharpe), PCA factor count, OU half-life, Kalman-filtered hedge ratio vs static OLS, triple-barrier meta-labeling, fractional differentiation, purged K-fold + embargo, and White's Reality Check implemented from scratch.

Lab 6 — Portfolio construction + risk: constrained mean-variance optimization, Ledoit-Wolf covariance shrinkage (and why it matters — compared side-by-side against the raw, noisy covariance weights), risk parity, fixed-fractional position sizing, a drawdown kill-switch with visualized equity curve, and portfolio VaR vs naive-sum VaR to quantify the diversification benefit.
