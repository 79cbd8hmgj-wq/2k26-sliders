# Portland roster snapshot — evidence and tracking plan

**Origin:** Two user-supplied screenshots of MyNBA → Association Roster Viewer → Portland Trail Blazers → Simple. Captured in conversation 2026-10-13.

The dataset [portland-roster-snapshot.csv](../data/portland-roster-snapshot.csv) transcribes the **visible** roster rows: display name, position, age, overall, category grades, potential grade and visible two-way indicators. Letter grades are approximate screen transcriptions and **cannot substitute for numeric attributes**. Note the roster may be custom, updated, or mid-save and should not be assumed to reflect a verified release-date roster. The display has green up-arrow +1 modifiers for some players; these do **not prove permanent development**.

**Unconfirmed:** Whether this screenshot predates any simulation, what sliders are active, the meaning of the +1 modifiers, individual attribute ratings, badge values, potential numeric values, peak ages, roster edits, training plans, or contract state.

## Selected detail-screen observations

- Damian Lillard: PG, 35, 89 OVR in list. Selected-player header shows 6'2", 200 lbs, wingspan 6'8", age 35, archetype `Versatile Paint Bully`, 18 total shown badges, 2 years / $27.50M contract displayed. The archetype text may seem unusual; preserve what was shown, don't "fix" to a more plausible role.
- Chris Youngblood: SG/SF in selected header (row lists SG), 23, 68 OVR; 6'4", 221 lbs, 6'8" wingspan; archetype `Sharpshooting Cleaner`; displayed 0 total badges, listed on a two-way contract. The screenshot's small salary text is hard to parse, so no salary amount was transcribed.
- Two-way visual marker: C. Love, J. Kent, C. Youngblood. Confirm in-game before using as an exact contractual fact.

## Players to measure closely in first pass

| Profile | Player | Why it matters |
|---|---|---|
| Aging scoring superstar | D. Lillard, 35, 89 | Athletic decline vs shooting/playmaking longevity |
| Aging defender/playmaker | J. Holiday, 35, 83 | Defensive awareness/skills vs quickness decline |
| Late-prime veteran forward | J. Grant, 31, 82 | Post-prime attribute divergence |
| Young star-level forward | D. Avdija, 24, 88 | Ceiling and whether OVR expands too much |
| Traditional defensive center | D. Clingan, 21, 84 | Size and rebounding development vs forced 3PT growth |
| Athletic scoring wing | S. Sharpe, 22, 84 | Athletic growth and offensive skill adaptation |
| Developing point guard | S. Henderson, 21, 81 | Growth, accuracy and decision-making |
| Defensive specialist | T. Camara, 25, 82 | Maintaining a defensively oriented role |
| Injury-sensitive athletic center | R. Williams III, 28, 80 | Durability and role change |
| Raw center | Y. Hansen, 20, 70 | Upside, bust rate, uneven improvements |
| Older prospect / bench scorer | C. Love, 24, 76 | Role and late-maturing skills |
| Fringe two-way prospect | C. Youngblood, 23, 68 | Whether low-OVR players develop too easily |
| Extra defensive specialist control | M. Thybulle, 28, 76 | Role-player specialization |

Track other players too; this is a *sample*, not a proposed roster purge.

## Next screenshot checklist

1. Numeric player attributes, not only the Simple letter grades.
2. Numeric potential, floor/ceiling, boom/bust settings if exposed, peak start/end age, and personality/mentorship variables.
3. Tendency pages, shooting percentages and attempts, badges, and actual minutes.
4. Current MyNBA progression, regression, and attribute-specific growth/peak/decline sliders.
5. Confirmation that a pre-simulation baseline save exists.

Only after those are collected should we decide whether existing player edits are necessary.
