# Ballot Access — The 50-State Database

**This is where independent campaigns go to die — quietly, on a deadline nobody told them about.**

Ballot access is the single most valuable dataset this project can build: for every state, exactly what an *unaffiliated / independent* candidate must do to get on the ballot, verified against the official source.

## What each state file must contain

Create files as `states/<state-slug>.md` using this template:

```text
# <State> — Independent / Unaffiliated Ballot Access

Office covered: (U.S. House / State House / State Senate / statewide — one section each)

## Requirements
- Filing form(s):
- Signature requirement: (number, and basis — e.g. % of last vote, % of registered voters)
- Signature gathering window:
- Filing deadline:
- Filing fee (or fee-waiver / in-lieu signatures):
- Party-affiliation cutoff: (e.g. must not have been registered with a party since…)
- Sore-loser rule: (may a primary loser run as an independent?)
- Ballot label allowed: (e.g. "Independent", "Unaffiliated", candidate-chosen)

## Official source
- <Secretary of State / Board of Elections page title + URL>
- Election code citation:

last_verified: YYYY-MM-DD
verified_by: <GitHub handle>

## Gotchas
- (the thing that trips everyone up in this state — notarization, district residency proof, circulator rules…)
```

## Rules for contributors

1. **Official sources only.** Secretary of State, state board of elections, or the election code itself. News articles and Wikipedia can *point* you there; they are never the citation.
2. **Date everything.** An undated rule is a rumor. Rules change after every legislative session.
3. **One state, done well, beats ten states guessed.** If you cannot verify a field, write `UNVERIFIED` — never fill a gap from memory.
4. **Flag the killers.** Missed deadlines, circulator-residency rules, and affiliation cutoffs deserve a ⚠️ at the top of the file.

## Why this gets the project noticed — and used

Every journalist, researcher, and would-be candidate who Googles *"how many signatures does an independent need in [state]"* should land here. Accuracy is the marketing.

## Status

| Region | States verified |
|---|---|
| All | **2 / 50** — California, Texas (verified 2026-11-05; see `states/california.md` and `states/texas.md`, closing issues #1 and #2). Pick yours in [CONTRIBUTING.md](../CONTRIBUTING.md) |

Open a *Verify a state* issue before you start, so two people don't duplicate the same state.
