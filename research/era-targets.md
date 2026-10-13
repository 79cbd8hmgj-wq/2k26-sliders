# 2006–2017 basketball: project style and provisional statistical benchmarks

## Accepted project choices

- **Style target:** NBA basketball watched from roughly 2006 through 2017. This is an era *blend*, not a claim that all those seasons played identically.
- **Suggested statistical center:** roughly 2010–2014, with era-appropriate styles ranging from the 2006–07 Suns through the 2016–17 Warriors and defense-oriented Grizzlies.
- **Scope:** realism in human-controlled games, CPU-vs-CPU games, full-season simulations, and long-term MyNBA league management.
- **Dynasty:** user eventually builds an expansion team and aims for several championships; realism must apply fairly to opponents.

## Provisional blended-era game benchmarks

These are **targets proposed during the conversation**, **not measured NBA 2K26 outputs** and **not fully source-audited NBA historical measurements**. Verify historical data from an authoritative league-season dataset before declaring a statistical calibration complete.

| Per-team, per-game metric | Proposed blended target |
|---|---|
| Points | 100–103 |
| Pace (possessions per 48 min) | 92–95 |
| Three-point attempts | 19–23 |
| Free-throw attempts | 23–25 |
| Field goal percentage | 45–46% |
| Three-point percentage | 35–36% |
| Assists | 21–23 |
| Turnovers | 14–15 |
| Offensive rebounds | 10–12 |

### Season anchor values discussed (verification pending)

| Season | PPG | Pace | 3PA/G | FTA/G |
|---|---:|---:|---:|---:|
| 2006–07 | 98.7 | 91.9 | 16.9 | 26.1 |
| 2010–11 | 99.6 | 92.1 | 18.0 | 24.4 |
| 2013–14 | 101.0 | 93.9 | 21.5 | 23.6 |
| 2016–17 | 105.6 | 96.4 | 27.0 | 23.1 |

These figures were cited in prior assistant discussion but **the underlying primary datasets have not yet been imported into this repository**. Don't conflate them with audited source data.

## Style is more than aggregate stats

- Midrange and post creation should be prevalent for the right players, not automatically high-efficiency for everyone.
- Physical defense and meaningful drives/paint contact matter, but real fouls should emerge from play rather than every whistle being forced.
- Traditional bigs can have valuable interior roles.
- Teams must retain distinct offensive identities (fast-break Suns, grind-it-out Grizzlies, ball-movement Spurs, perimeter-shooting Warriors).
- Modern default team/individual tendencies and playbooks may override desired shot selection, so sliders alone may not be sufficient.
- Three-point **attempt rate, shooting skill, and success percentage are separate variables**.

## Calibration rule

Do not equate game slider values with observed percentages. Set a versioned default baseline, simulate games, measure league outputs, and change one *group of related controls* at a time.

## Future source acquisition

- Download audited NBA league totals/averages for each regular season 2006–07 through 2016–17.
- Record pace, ORtg, PPG, FGA, shot-distance mix (where available), 3PA, 3P%, 2P%, FTA, assists, turnover rate, rebound rates, foul rate.
- Add team-season distributions (ranges and variance, not only league averages), and relevant position/usage splits.
- Include primary source URLs, season identifiers, data definitions, and download timestamps. Do not label an estimate as measured.
