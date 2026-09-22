# BB — primary record (compile-only)
retrieve_date: 2026-09-22
live_attach: forbidden
depth: Country file only

## ONE primary
- url: https://treasury.gov.bb/content/treasury-bills-and-important-dates
- agency: Treasury Department (issuer-side); Government of Barbados / MoF
- record: Treasury Bills and Important Dates — issue notices + Results of Treasury Bills Auction PDFs
- label: we-have-a-record
- basis: Evidence (curl HTTP 200 2026-09-22; Scout WebFetch + sample results PDFs 200)
- figures_supported: existence of official issuer-side T-bill notice and auction-results PDF class
- figures_blank_not_proven: transcribed PDF allotment/yield/volume cells; inventing APIs

## Co-primary
- schedule: https://www.centralbank.org.bb/treasury-bills-schedule
- issue_notice_sample: https://www.centralbank.org.bb/news/general-press-release/treasury-bills-issue-1040
- mandate: https://www.centralbank.org.bb/investments
- label: we-have-a-record
- basis: Evidence (curl HTTP 200 this pass)
- role: CBB fiscal-agent calendar, issue notices, mandate

## Scope
- BSE Fixed Income: secondary only
- BOSS+: retail/savings under CBB fiscal agent (distinct from competitive T-bill results)
- finance.gov.bb: not-proven — do not invent
