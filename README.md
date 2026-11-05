# 3rd-Party Politics — Without the Party

**Don't build a third party. Build the rails for independent candidates.**

A party-free platform to **recruit** credible independent candidates and steer them through the obvious tasks that kill most independent runs — **ballot access, signature gathering, compliance, fundraising, and direct-to-voter distribution.**

No party. No platform. No loyalty oath. Candidates answer only to their constituents.

**🌐 Live site: [3rd-party-politics.vercel.app](https://3rd-party-politics.vercel.app)**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Good first issues](https://img.shields.io/badge/good%20first%20issues-open-blue.svg)](https://github.com/chrbailey/3rd-Party-Politics/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)

> ⭐ **If you think voters should be able to hire a person, not rent a party — star this repo.** Stars are how other builders, researchers, and would-be candidates find it.

---

## The problem

A third party reproduces the exact problem it claims to fix: the same power dynamics as Democrats and Republicans. Everyone ends up leveraging the party for their own personal power.

And independents running alone face a wall that has nothing to do with their ideas:

- Ballot-access rules are different in all 50 states — deadlines, signature counts, fees, forms
- One missed filing or compliance error can end a campaign before it starts
- Parties own the donor lists, voter data, debate access, and media relationships
- There is no one whose job is to *find* good candidates in the first place

Ross Perot got ~19% of the presidential vote in 1992 with none of the infrastructure below. The demand is proven. The distribution is missing.

## The idea: a recruiter + rails, not a party

In business, the leader doesn't wait for talent to apply — **the leader recruits it.** Politics is the one field where only parties do that job. That is the key fix.

So this project does only two things:

### 1. Recruit like an owner, not a party boss

A small, leader-led **steering group** actively recruits proven operators for specific, winnable races — mayors, builders, veterans, business owners, community leaders — people with a track record of actually delivering something.

- Target **25–50 winnable districts first**, not a symbolic presidential run
- Vet for track record and local trust, **not ideology**
- No platform to sign, no loyalty oath, no dues

See [`steering/`](steering/) for the charter and its hard limits, and [`recruiting/`](recruiting/) for the scorecard and district-targeting method.

### 2. Provide the rails as a service

The steering group steers each candidate through the **most obvious tasks** — the unglamorous work parties quietly do for their own:

| Rail | What it means in practice |
|---|---|
| **Ballot access** | 50-state rules, deadlines, signature targets, filing fees, legal review |
| **Compliance** | FEC / state registration, treasurer, reporting calendar, disclaimers |
| **Fundraising** | Small-donor stack from day one, transparent pricing, candidate owns the list |
| **Distribution** | Debate access, earned media, podcasts, town halls, voter outreach |
| **Back office** | Staffing playbooks, website, data, operations checklists |

See [`ballot-access/`](ballot-access/), [`playbooks/`](playbooks/), and [`templates/`](templates/).

## The power dynamic is the product

Think **Shopify, not a franchise** — and **Cost Plus, not a gatekeeper**:

- The platform **serves** the candidate; it does not own the candidate
- The candidate signs a public, written **[Constituent Commitment](templates/constituent-commitment.md)** — to voters, not to us
- The candidate **owns their donor list and data** and can leave at any time, taking both with them
- The steering group sets **no policy positions** and issues **no whip votes**
- Fees, if any, are flat and published — no percentage of power

If the platform ever tries to control a candidate, the candidate walks. That exit right is what keeps this from becoming a third party.

## Non-negotiables

1. **No party** — no ballot line owned by us, no party registration, no party brand on the candidate
2. **No platform** — each candidate commits only to their own constituents, in their own words
3. **No loyalty oath** — support is a service, never obedience
4. **Candidate owns everything** — donors, data, lists, content, accounts
5. **Process, not ideology** — we steer the *tasks*, never the *positions*
6. **Public by default** — playbooks, scorecards, rules data, and commitments are open in this repo

## Roadmap

- [x] Manifesto, steering charter, and recruiting scorecard (v0.1 — this repo)
- [ ] Ballot-access database: verified rules for all 50 states, with official sources
- [ ] Target-district method applied: first 25–50 districts scored and published
- [ ] Candidate launch playbook: filing → fundraising → first 30 days
- [ ] First recruited candidates: steering support through one full filing cycle
- [ ] Constituent scorecard: a public template for grading promises vs. votes

Full roadmap: [ROADMAP.md](ROADMAP.md)

## How to help — good first tasks

You do **not** need to be a political insider. The highest-value early work is research and checklists:

- **Verify one state** — check a state's independent ballot-access rules against its official Secretary of State source and open a PR (see [`ballot-access/`](ballot-access/))
- **Score a district** — apply the targeting method in [`recruiting/target-districts.md`](recruiting/target-districts.md)
- **Improve a playbook** — if you've run anything (a campaign, a business, a compliance function), your checklist is gold
- **Argue with us** — open an issue if a guardrail is missing. Becoming-a-party is the failure mode; help us design against it

Read [CONTRIBUTING.md](CONTRIBUTING.md), then pick a [good first issue](https://github.com/chrbailey/3rd-Party-Politics/issues).

## Repository map

```text
ballot-access/   50-state rules, deadlines, and signature requirements — with sources
recruiting/      Candidate scorecard + how target districts are chosen
steering/        Steering group charter: what it does, and what it may never do
playbooks/       Launch, compliance, fundraising, and distribution checklists
templates/       Constituent Commitment, launch emails, town-hall formats
.github/         Issue templates for state verification, districts, and candidates
```

## Who this is for

- Voters who are done choosing between two party brands
- Credible local leaders who would run — if running didn't require building a machine first
- Builders, researchers, election lawyers, and operators who want to build the machine *as a public good*
- Anyone asking: *"What would it take for a candidate to get on the ballot and win on what they commit to do — with no party involved?"*

## License

MIT — see [LICENSE](LICENSE). Take the playbooks, fork the rails, run a better version. The point is distribution, not control.

---

**Keywords for search:** independent candidates, third party alternative, ballot access reform, no party politics, candidate recruitment, direct-to-voter, open primaries, ranked-choice voting, small-donor fundraising, campaign infrastructure, unaffiliated candidates, Perot 19%.
