# Target Districts — Method

Start where an independent can actually win, with a candidate voters already trust. **25–50 districts first.** A short, winnable list beats a national fantasy map.

## Score each district 0–3 on each factor

| Factor | What to measure | Where to get it |
|---|---|---|
| **Voter independence** | Unaffiliated / independent registration share; split-ticket history | State voter stats, past results |
| **Party weakness** | Incumbent retiring, scandal, extreme nominee risk, low incumbent approval | News, filings, polling |
| **Margin reality** | Last two cycles decided by <10 pts, or uncontested (untested incumbent) | Official election results |
| **Ballot difficulty** | Signature count, deadline, fee for independents — lower is better | [`../ballot-access/`](../ballot-access/) |
| **Local talent pool** | Known, trusted operators who fit the [scorecard](candidate-scorecard.md) | Local knowledge, public record |
| **Media reachability** | Local media still exists; podcasts / community channels are strong | Market research |
| **Fundraising plausibility** | Local small-donor base, business community, diaspora support | Judgment, disclosed as such |

**Publish the scores and the sources.** A district we cannot score honestly is not a target yet.

## Sequencing

1. **Wave 1 (prove it):** 5–10 districts — easiest ballots, strongest talent, weakest incumbents. State legislature and U.S. House included; do not start with a presidential race.
2. **Wave 2 (repeat it):** expand to 25–50 using Wave 1's real costs, timelines, and failure notes.
3. **Wave 3 (scale it):** only after two cycles of published post-mortems.

## Anti-patterns

- Targeting a district because it is famous, rather than winnable
- A map drawn in one city, for places no one on the team has lived
- Counting a district as a target before the ballot-access file for its state is verified
- Recruiting a candidate first and inventing the district math afterwards — score the district, *then* recruit

## District file template

```text
District:
Office / cycle:
Incumbent / status:
Scores (0-3 each, with source links):
  Voter independence:
  Party weakness:
  Margin reality:
  Ballot difficulty:
  Local talent pool:
  Media reachability:
  Fundraising plausibility:
Total /21:
Ballot-access state file verified? (Y/N, link)
Known talent (public figures only):
Biggest risk:
Last updated:
```
