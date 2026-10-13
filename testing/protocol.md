# MyNBA 2K26 realism testing protocol — v0 (pre-experiment)

## Goal and invariants

Achieve a believable **2006–2017-style NBA** in (1) user-played games, (2) CPU-vs-CPU games and (3) MyNBA season simulations. Also sustain 10–25 seasons of equitable, realistic player development suitable for an expansion dynasty.

**Nothing measured yet.** Screenshots are *roster and third-party slider references*, not experimental validation.

## Phase A — untouched baseline

1. Create a **new testing MyNBA save** separate from the eventual expansion dynasty.
2. Confirm calendar year, custom roster choice, injuries, sliders, quarter length, team selections and game/simulation modes.
3. Save an untouched `baseline-start` file before simulating; document a settings export or photos.
4. Record league-wide player IDs, team, age, OVR and **numeric** ratings; note if any player is already modified or progressing.
5. Record proposed Portland tracked players and 30–40 league-wide controls balanced by age, role, team, potential and 3PT baseline.
6. Save the baseline season results and (where practical) the snapshots preceding each offseason.

## Phase B — season simulation

1. At default sliders, simulate a full season; record all team totals/averages, and our tracked player-season records.
2. Note minutes, games, attempts, position, role, training, injuries and team changes.
3. Repeat to year 5 with year-by-year roster measurements, not only OVR changes at the end.
4. Prefer multiple independent saved runs if the engine's randomization can be re-sampled; never claim a fixed seed is possible until verified.
5. Track 90+ OVR counts, late-bloomers, number of viable big-man shooters, all-star distributions, and free-agent roster quality.
6. Note all roster/rule/slider adjustments and distinguish experimental branches from the untouched baseline.

## Phase C — controlled progression tests

- Change **one group** per experiment: e.g. attribute-specific 3PT growth, peak ages, regression, or training.
- Match starting roster, settings and simulation mode to the baseline. Repeat when random variation is material.
- Measure attributes and production independently: a 3PT attempts increase is not necessarily a 3PT rating increase.
- Report median and distribution of changes by age band, position, and player baseline.
- Mark any manual player fixes as **interventions**, not natural progression.
- Do not use progression settings so generous that every young prospect becomes a star.

## Phase D — game-play tests

- Run recorded 12-minute-quarter sample games (quarter length itself to be decided), using separate Human/CPU and CPU/CPU conditions when necessary.
- Record possessions, FGA/3PA/FTA, shooting rates, turnover types, fouls, offensive rebounds, pace, point totals and distribution of attempts by zone.
- Diagnose *mechanism*: low FTA might require contact/foul or drive behavior changes; high FG% could reflect defense, shot mix or conversion.
- Keep documented game settings constant within each matched comparison.
- Team playbooks and individual tendencies may also require editing or controlling, not just global sliders.

## Phase E — long term expansion dynasty

Only after 5–10 season tests and multi-game calibration: establish expansion rules and a versioned `v1.0` slider file. Track CPU parity, CBA/economy, contracts, player growth, trades and injury rates across 15–25 years.

## Test roster sample

Portland screenshot identified 18 visible players; details in `data/portland-roster-snapshot.csv`. Priority roles:

- Young raw PG: Scoot Henderson
- Young athletic wing: Shaedon Sharpe
- Traditional big: Donovan Clingan
- Young high-level forward: Deni Avdija
- Defensive specialist: Toumani Camara / Matisse Thybulle
- Skilled older guard: Damian Lillard / Jrue Holiday
- Injury-sensitive big: Robert Williams III
- Fringe player: Chris Youngblood
- Raw young big: Yang Hansen
- Prime-to-veteran transition: Jerami Grant
- Older developing guard: Caleb Love

Do not needlessly change the real team lineup for the test; other archetypes can be tracked on other teams.

## Data completeness levels

- `screenshot` = user image observation (snapshot age/overall).
- `baseline_unconfirmed` = user has not certified the save as pristine.
- `baseline_confirmed` = user confirms clean save and time of snapshot.
- `simulation_measured` = actual season statistics exported/manually recorded.
- `slider_trial` = controlled experiment with setting differences recorded.

## Controls and interpretation

1. Playing time and usage are not pure attribute development; log separately.
2. Do not compare raw simulated game totals with reduced quarter-length games without normalization.
3. No roster-wide or personal corrections during a control run.
4. Preserve all versions and avoid silently overwriting baselines.
5. **Do not infer any attribute or aging mechanic merely from a user-interface label**; inspect and test it.
6. Historical data needs reliable primary/aggregator sourcing and annual team variance, not only grand means.

## Data entry

- `data/player-season-template.csv`: make one row per player per season per experimental run; do not overwrite earlier seasons.
- `data/team-season-template.csv`: one row per team per season per experimental run.
- `data/game-test-template.csv`: one row per played or spectated game. Additional per-player box scores can be attached separately.

Blank cells mean uncollected, **not zero**.
