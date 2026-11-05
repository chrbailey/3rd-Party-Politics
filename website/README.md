# Website / Portal

The public site for 3rd-Party Politics. Plain static HTML/CSS — no build step, no framework, no database.

## Deploy (Vercel)

- Project root directory: `website`
- Framework preset: Other / None (static)
- Every push to `main` redeploys automatically once the project is linked to this repo.

## Why no backend database (yet)

GitHub *is* the backend for v1, on purpose:

- All content (ballot-access data, playbooks, scorecards, commitments) is public and versioned — Git gives history, review, and rollback for free
- All intake is public by design: verify-a-state, score-a-district, and suggest-a-candidate are GitHub issue templates
- There is no private user data to store, so there is nothing a database would protect or power

**Add a database when — and only when — the portal takes private submissions** (candidate applications, volunteer signups, an email list). At that point the right move is:

1. A managed Postgres (Vercel Postgres / Neon, or Supabase) — never a self-hosted box
2. A single small form endpoint (Vercel Function) writing to it
3. A hard rule, matching the project's principles: **private submissions never go in GitHub issues**, and candidate data belongs to the candidate
