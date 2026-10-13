# First visible NBA 2K26 simulation output — 2025–26 context

Source: seven user screenshots shared 2026-10-13. They show MyNBA Association League Leaders (per game and per 100 possessions) and Team Stats: Regular. The 2026 date and Flagg ROY headline suggest a late 2025–26 season checkpoint, but **exact completion status, save settings, and whether this is the same baseline as Portland roster screenshots are not confirmed**.

## What is recorded

- 27 visible team rows, with PPG, opponent PPG, scoring differential, FGM/FGA, FG%, 3PM/3PA/3P%, FTM/FTA. Three teams not visible. Values are rounded exactly as shown; internal sums may differ slightly.
- Top 18 scorers, per-game visible columns. Giannis 3P% is DNQ, left blank in CSV.
- The per-100-possessions screenshot is *not* a league pace measurement; it is a player rate normalization.
- Per-100 SGA: 52.6 points, 5.3 rebounds, 8.3 assists, 2.5 steals, 0.9 blocks, 3.4 turnovers, 3.5 fouls, 18.6 FGM, 29.6 FGA, 3.1 3PM, 6.0 3PA, 12.4 FTM.
- SGA per game: 36.7 PPG, .627 FG, .519 3P, 2.2 3PM. The efficiency is a standout anomaly relative to our historical target.
- Oklahoma City: 128.0 PPG, .539 FG, 29.6 3PA, .393 3P.
- Portland: 121.9 PPG, .527 FG, 30.8 3PA, .388 3P.
- Lowest PPG among visible teams: Warriors 108.9; highest: Thunder 128.0.
- **Diagnostic priority:** scoring volume and FG conversion appear too high for the proposed blended 2006–2017 era, and three-point attempt volume is above the provisional 19–23 target for many teams. This is a *comparison against a project objective*, not a statement that the sim is broken or that a single slider causes it.
- **Do not change sliders yet** without recording the active simulator, shot-type, shot-percentage, and game settings. Also measure turnovers, fouls, possessions and pace from further screenshots.
- Player card highlights: SGA OVR 98 age 27; Tyrese Haliburton OVR 83 age 26 and torn left MCL (season); Zion Williamson OVR 83 age 25 and strained right hip (4–6 weeks). These are incidental player-card details, not scoring-leader stats.

See `data/first-sim-team-stats.csv` and `data/first-sim-scoring-leaders.csv`. Both are **observed**, not independently validated against exported save files.
