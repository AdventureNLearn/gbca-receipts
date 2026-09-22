# BD — primary record (compile-only)
retrieve_date: 2026-09-22
live_attach: forbidden
depth: Country file only

## ONE primary
- url: https://www.bb.org.bd/en/index.php/monetaryactivity/treasury
- agency: Bangladesh Bank (auction agent); issuer = Government of Bangladesh / MoF
- record: Primary Issue/Auction of T-Bills and Treasury Bonds — live allotment table class
- label: we-have-a-record
- basis: Evidence (Scout WebSearch indexed live Sep 2026 auction rows); box curl/WebFetch intermittent this pass
- figures_supported: existence of official BB T-bill/BGTB primary-auction results door
- figures_blank_not_proven: transcribed allotment/yield/volume cells; inventing APIs

## Co-primary
- auc_calendar: https://www.bb.org.bd/en/index.php/monetaryactivity/auc_calendar
- press_release: https://www.bb.org.bd/en/index.php/mediaroom/press_release
- BGIS: https://www.bb.org.bd/en/index.php/monetaryactivity/bgis_home (+ auc_notice_sukuk)
- label: we-have-a-record (Scout-indexed)

## Scope
- DSE / CSE: secondary only
- MoF live allotment UI: not-proven
- SPFMS MTDS: supporting (HTTP 200 this pass)
- ERD: external-debt supporting
