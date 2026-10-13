# Attribute-specific progression and regression — research questions

This file preserves **project requirements and hypotheses**, not proven NBA 2K26 rules.

## Core objective

Track player careers across 5–25 MyNBA seasons with **nonuniform growth and decline**. A player's overall rating is an inadequate proxy for basketball ability or career outcome.

### Desired behaviors

1. Athletic peaks are generally earlier; speed, acceleration, vertical and injury recovery tend to become more vulnerable with age.
2. Technical skills may continue improving with experience (midrange, 3PT for a *subset*, post footwork, passing, positioning).
3. Awareness and decision-making can improve or remain strong while athletic ability declines.
4. A player may change role without improving OVR; a late-career center may shoot more threes but rebound/finish less.
5. Low potential, injuries, poor minutes, training, and luck can stall or redirect careers.
6. Some players should never develop useful outside shooting, even when they train it.
7. There should be late bloomers and post-prime reinventions, but they must be **uncommon and context dependent**, not universal.
8. CPU teams must receive the same conditions and possible correction policy as user teams.

### Real-player archetypes to study, NOT deterministic scripts

| Player example | Pattern to test |
|---|---|
| Marc Gasol | Late-career increased 3-point volume while adapting role |
| Brook Lopez | Major move from post scoring toward outside shooting |
| Kyle Lowry | Late-prime improvement and changing responsibility |
| Paul Millsap | Incremental outside shooting adaptation |
| Tony Allen | Defense-first identity without automatic outside scoring growth |
| Derrick Rose | Injuries affecting athleticism and role |

**Important:** shot attempts and conversion percentages are not individual ratings. Role change, coaching, volume, and selection effects matter.

### Preliminary attribute-group matrix (qualitative hypothesis)

| Group | Young | Prime | Veteran |
|---|---|---|---|
| Speed / acceleration / vertical | Early gains | Earlier peak | Decline more likely |
| Strength | Slower gains | Maintain/peak | Relatively slower decline |
| Post technique / footwork | Gradual growth | Refine | Often durable |
| Passing vision / awareness | Experience-dependent | Improve | May remain strong |
| Midrange / FT | Variable | Maintain/refine | Often more durable than athleticism |
| 3PT skill | **Player-dependent** | Conditional growth | Rare late transformation possible |
| Rim protection | Mix of athleticism/positioning | Peak varies | May trade lift for positioning |
| Durability | Individual | Individual | Injury risk may grow |

This is **not** a formula to impose on every player.

## What 2K settings must be inspected before tuning

- Global Player Progression and Regression Rates, if exposed.
- Attribute-by-attribute Growth / Peak / Decline controls and their actual definitions/ranges.
- Individual numeric potential, potential floors/ceilings, ages at peak start/end, and boom/bust values, if exposed.
- Training intensity, focused drills, coaching and morale impacts.
- Tendencies, shot selections, badges and minutes.
- Whether the engine treats human and CPU development differently.

If controls are unavailable or their effects undocumented, measure them experimentally rather than inventing assumed mechanics.

## Quantitative evaluations to construct

- Mean/median and variance in year-to-year **attribute deltas**, stratified by age, position, role, potential bracket, and minutes.
- Rate at which low-3PT bigs become competent shooters; compare with historical cohorts and note sample sizes.
- Share of players with OVR gains/losses and frequency of late breakouts.
- Attribute peak-age distributions and post-prime divergences.
- League-wide ratings inflation (distribution of 60–69, 70–79, 80–89, 90+ after 5/10/15 seasons).
- Transition from starter to reserve; retirements, injury effects and roster turnover.
- New-draft-class talent distributions (all-star rate, role-player rate, bust rate).

## Correction policy (selected by user)

**Hybrid / realism corrections only.** Start with neutral automated sliders. Permit exceptional **league-wide, symmetric, logged** manual interventions after diagnosis; record affected players, rationale, before/after attributes and re-test. No one-way benefits for the eventual expansion franchise.

No player-specific corrections or guaranteed outcomes are approved yet.
