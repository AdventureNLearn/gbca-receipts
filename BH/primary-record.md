# BH — primary record (compile-only)
retrieve_date: 2026-09-22
live_attach: forbidden
depth: Country file only

## ONE primary
- url: https://www.cbb.gov.bh/media_category/treasury-bills/
- sample: https://www.cbb.gov.bh/media-center/cbbs-monthly-issue-of-treasury-bills-oversubscribed-76/
- agency: CBB (auction agent); issuer = Government of Bahrain / MOFNE
- record: CBB media category Government Securities / Treasury Bills — indexed primary-allotment press releases
- label: we-have-a-record
- basis: Evidence (curl HTTP 200 category + sample 2026-09-22)
- figures_supported: existence of official allotment press-release class (T-bill / GDB / sukuk peers)
- figures_blank_not_proven: transcribed allotment/yield/volume cells; IDS; inventing allotment APIs

## Co-primary
- url: https://www.cbb.gov.bh/government-securities/
- label: we-have-a-record
- basis: Evidence (WebFetch 200)
- role: GTS program hub + Issuance Calendar; auction procedures; press-release allotment disclosure described

## Scope
- Bahrain Bourse: secondary only (+ occasional GDB subscription channel)
- MOFNE live allotment UI: not-proven
- CBB /apis/: FX ExchangeRate only — not allotment
