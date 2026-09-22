# AO — primary record (compile-only)
retrieve_date: 2026-09-22
live_attach: forbidden
depth: Country file only

## ONE primary (debt-management disclosure hub — not live allotment)
- url: https://ugd.minfin.gov.ao/
- agency: UGD / MINFIN
- record: Portal Institucional — Unidade de Gestão da Dívida Pública
- label: we-have-a-record
- basis: Evidence (HTTP 200; title Portal Institucional - UGD)
- figures_supported: institutional / disclosure hub existence
- figures_blank_not_proven: live auction allotment fields; PAE/boletim numeric tables; IDS
- note: SPA-heavy; WebFetch timed out — amounts not read from bulletins this pass

## Co-primary companion (instrument class — not allotment)
- url: https://portaldoinvestidor.minfin.gov.ao/titulos-do-tesouro/conheca-os-titulos-do-tesouro
- record: Bilhetes de Tesouro (BT) + Obrigações do Tesouro Não Reajustáveis (OT-NR) definitions
- label: we-have-a-record
- basis: Evidence (live WebFetch 2026-09-22)

## Live open allotment UI
- status: [UNKNOWN] / not-proven
- rejected_as_primary: BODIVA (secondary); portaldocontribuinte (tax); SIGD-ECM (auth wall)
