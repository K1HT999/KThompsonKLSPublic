Kalshi weather-market strategy using alternative data.

The original goal was to use high-frequency weather data to price temperature longshots more accurately than the market.
After correcting for executable pricing, fees, stale fields, and leakage, the broad model was less impressive than expected.
But the process uncovered something more interesting: A specific subset of temperature longshot NO contracts showed persistent YES-side overpricing. 

Backtest Results:
307 trades
300 wins
7 misses
97.7% win rate
+692.4c per one-contract basket
Observed misses: 7
Break-even expected misses: 13.9
p-value: 0.0287
I am not publishing the exact contract universe, city, price bands, filters, thresholds, or live rule because those are the parts most likely to decay.

