# GXO-Knowledge-Transfer-Project

## Confidential-Safe Public Pack

This repository publishes methodology and analysis logic only.
No confidential source data or derived data artefacts are included.

## Scope
- Included: notebooks with logic/process (outputs removed).
- Included: notes describing approach.
- Excluded: proprietary datasets, generated tables/maps, and derived exports.

## Private input contract
To run notebook workflows locally, provide private files outside this repository via `DATA_DIR`.

Expected private input filenames:
- `sys_order_consolidation.xlsx`
- `address_with_geo.xlsx`
- any additional private intermediate files referenced by notebook code

## Local setup
1. Copy `.env.example` to `.env` and set `DATA_DIR` to your local private data path.
2. Keep private files out of this repository.
3. Run notebooks locally with your private data mounted in `DATA_DIR`.

## Confidentiality policy
The original task brief and associated datasets are treated as confidential.
All versions derived from those datasets are intentionally excluded from version control.
