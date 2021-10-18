# momentum
* First file (Dual_GEM) is the realisation of Dual Momentum Trading strategy of Gary Antonacci
https://dualmomentum.net/
Basically we first check the relative momentum between US equities (SPY) and International equities (EFA), and choose the best market, then we check absolute momentum against SHY ETF (short term treauries) and if momentum is positive we invest into the chosen market (SPY/EFA) otherwise we invest to bonds (TLT).
* Second file (2DM) is the improvement of the basic strategy. It's a composite strategy based on signals of the two models with shorter (63 trading days) and longer(84 trading days) loockback periods. If both models agree on signals the composite strategy allocates to bonds/equities, if they disagree then shorter lookback period is used for shift to bonds, and longer to shift to equities.
