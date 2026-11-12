# AAD portfolio — reframed for Harvard AA&D Director of Development Strategy (003903SR)

Drop-in replacement for the live narissa-pgm.github.io/AAD pages, reframed for the
**Director of Development Strategy** role in Harvard Alumni Affairs and Development
(University Development / UDAS), requisition 003903SR.

## Upload
- Every `*.html` in this folder -> repository root (overwrite).
- `assets/aad-model.js`, `assets/suite.js`, `assets/visual-explorer.js` -> the repo's `assets/` folder.
- Everything else (CSS, images, videos) is unchanged.

Commit and push; GitHub Pages redeploys.

## What changed
- Role identity: "Director of Stewardship Reporting" -> "Director, Development Strategy" (department stays
  Harvard Alumni Affairs and Development; University stays Harvard).
- Old posting link (jid-2347) -> the 003903SR posting.
- Product/page names: Development Strategy Platform / Suite / Playbook / Program Office / Workframe; portfolio title.
- Coverage matrix (`assets/aad-model.js`): rewritten to the 14 duties in four areas of this role —
  Prospect Strategy & Pipeline; Solicitation Portfolio & Governance; Leadership Programs & Communications;
  Team & Operations — each mapped to the page that demonstrates it.
- career-profile.html: new "Current projects & forward plan" part — current practice, a proposed first-year
  plan (Q1 top-prospect baseline, Q2 pipeline cadence, Q3 $10M+ tracker and Gift Policy Committee packets,
  Q4 committee onboarding and event calendar) and a 36-month horizon using One Harvard, SMARTER and VERITAS.
- Page-level framing: titles, meta descriptions, heroes, archive area headings, FAS briefing-cycle pilot framing,
  signature blocks.
- Shared chrome rename: "Connected stewardship program navigation" -> "Connected AA&D development strategy navigation".

## Data discipline (kept)
All figures remain labelled PUBLISHED (sourced) or SYNTHESIZED (illustrative); plans are PROPOSED.
Numbers, data arrays, synthetic donor records, KPI targets, schedules, gates and provenance values are unchanged.
No page claims HBS/AE&D affiliation, deployed systems, or institutional adoption.

## Provenance
Reframed from the live site fetched 2026-11-11 by exact string replacement; pages verified with lxml parsing and
script-tag counts against the fetched originals.
