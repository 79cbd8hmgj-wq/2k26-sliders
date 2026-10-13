# NBA 2K26 — 2006–2017 Realism & Expansion Dynasty

Research and calibration repository for a long-running NBA 2K26 MyNBA expansion-franchise save.

## Vision

Build a new expansion team into a multi-championship contender **without making development, roster building, or winning artificially easy**. Preserve the basketball identity of roughly **2006–2017**, rather than modeling only modern NBA play:

- Meaningful post play, midrange offense, physical drives, contact, rebounds, and varied team strategies.
- Distinct team and player identities (not every team or player becomes a three-point specialist).
- Realism across **user-played games**, **CPU-vs-CPU games**, and **simulated seasons**.
- Player attributes aging independently: athleticism may decline while shooting, passing, footwork, or awareness improves.
- Different career trajectories: late bloomers, early peaks, busts, specialists, injuries, and late-career reinventions.
- Occasional **neutral realism corrections**, if the engine produces implausible player development; no preferential help for the expansion team.

## Data and documents

| File | Purpose |
|---|---|
| [reference/screenshot-slider-reference.md](reference/screenshot-slider-reference.md) | Visible slider-setting transcription from 7 screenshots of a **third-party** Operation Sports set. **Not our endorsed sliders.** |
| [reference/screenshot-manifest.md](reference/screenshot-manifest.md) | Provenance and checksums of 9 original screenshots. Original binaries not yet in the repo. |
| [data/portland-roster-snapshot.csv](data/portland-roster-snapshot.csv) | Observed ages and overall ratings from two Portland roster screenshots. |
| [reference/portland-roster-notes.md](reference/portland-roster-notes.md) | What the screenshots can and cannot establish and priority players to track. |
| [research/era-targets.md](research/era-targets.md) | Era-selection rationale and **provisional** league-level statistical targets requiring source verification. |
| [research/player-development-hypotheses.md](research/player-development-hypotheses.md) | Aging/development model to test, not a claim of game mechanics. |
| [testing/protocol.md](testing/protocol.md) | Baseline / experimental control plan for game play, sim stats, and progression. |
| [data/player-season-template.csv](data/player-season-template.csv) | Blank per-season player measurement template. |
| [data/team-season-template.csv](data/team-season-template.csv) | Blank per-team seasonal statistics template. |
| [data/game-test-template.csv](data/game-test-template.csv) | Blank played/CPU-game statistical validation template. |

## Evidence labels

- **Observed screenshot**: transcribed from a user-supplied NBA 2K26 screen or third-party slider screenshot; report the origin.
- **Project preference**: choices agreed in conversation.
- **Provisional target**: a calibration objective, not a measured game or league result.
- **Hypothesis**: predicted behavior to evaluate experimentally.
- **Measured**: an actual saved season / game result (none yet).
- **Unverified**: cannot yet be established, e.g. whether the roster snapshot preceded season simulation.

## Status (2026-10-13)

The game and test franchise were not yet confirmed to have an untouched season-zero save. The Portland screens may reflect unknown prior progress. No actual 2K26 regression/progression experiments have been run here. **Do not silently treat the third-party slider values as our own final settings.**

## Immediate next steps

1. Save a clean MyNBA test file before making edits or simulating.
2. Record player numeric attributes, potential, individual peak ages, tendencies, roles, minutes, injuries, morale, and training.
3. Simulate a season at defaults and record team and player results alongside full season age/ratings changes.
4. Repeat with controlled slider changes, holding other parameters and rosters constant.
5. Analyze league-wide drift over 5–10+ seasons before starting the actual expansion dynasty.

Initial documentation prepared from the discussion and screenshots on 2026-10-13. Original image bytes are preserved in a separate user-downloadable ZIP backup, not stored in this GitHub repository yet.
