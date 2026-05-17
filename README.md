**Kalshi weather-market strategy NO Longshots.**

The original goal was to use high-frequency weather data to price temperature longshots more accurately than the market.
After correcting for executable pricing, fees, stale fields, and leakage, the broad model was less impressive than expected.
But the process uncovered something more interesting: A specific subset of temperature longshot NO contracts showed persistent YES-side overpricing. 

Rule:
```text
IF
12h to resolution upper-tail high-temperature contract
AND YES ask between 1c and 20c
THEN
Enter NO side
```

Backtest Results:
1047 trades
999 wins
48 misses
95.4% win rate
+258.8c per one-contract basket
Break-even expected misses: 50.9
p-value: 0.38
I am not publishing the exact contract universe or city.

**Author:** K. Thompson  
**Research Platform:** ThomPlatz Research  
**Contact:** thomplatzresearch@gmail.com 
