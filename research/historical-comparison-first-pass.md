# First historical comparison (research checkpoint)

Baseline: 27 photographed NBA 2K26 teams, configured 58-game completed season, default settings. CSV: default-team-stats-27-teams.csv.

| Metric | 2K26 photographed 27-team mean | NBA 2006-07 | NBA 2009-10 | NBA 2016-17 |
|---|---:|---:|---:|---:|
| Points/game | 118.33 | 98.7 | 100.4 | 105.6 |
| FG% | 51.05% (mean of team percentages) | 45.8% | 46.1% | 45.7% |
| 3PA/game | 32.16 | 16.9 | 18.1 | 27.0 |
| Pace | 99.59 | 91.9 | 92.7 | 96.4 |

Historical source: https://www.basketball-reference.com/leagues/NBA_stats_per_game.html

Observations: Baseline exceeds even 2016-17 in all four metrics. Relative to 2016-17: +12.73 PPG, +5.35 percentage points FG%, +5.16 3PA/game, +3.19 pace. Relative to 2009-10: +17.93 PPG, +4.95 points FG%, +14.06 3PA/game, +6.89 pace. The desired 2006-2017 identity should not be a single-year hard target; use an era blend with varied team identities and preserve star outliers.

Cautions: 27/30 teams only, unweighted team means versus league averages; compare as provisional. Pace may reflect game-engine definition differences. Do not apply slider changes yet. Check consistency of 3PM, 3PA and 3P% and estimate eFG%, offensive rating, shot distribution. Individual player development should be calibrated separately, with different skill trajectories and aging curves.