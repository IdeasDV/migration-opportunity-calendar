# Mini Update Deploy Candidate v1.2L2 FIX

Generated: 2026-06-12 16:05:52

## Scope

- Created final deploy candidate package with robust JSON inspection.
- Source preview package: C:\Users\danie\Migration_Opportunity_Calendar\outputs\public_preview_packages\migration_opportunity_calendar_MINI_PREVIEW_v1_2G_20260612_155420
- Deploy candidate: C:\Users\danie\Migration_Opportunity_Calendar\outputs\publication_packages\migration_opportunity_calendar_MINI_UPDATE_DEPLOY_CANDIDATE_v1_2L2_FIX_20260612_160551
- Master not modified.
- Inbox not modified.
- Source registry not modified.
- outputs\public_site not modified.
- Netlify/live site not deployed.

## Integrity

- Clean deploy candidate: True
- CSV rows: 25
- JSON rows normalized: 25
- Added records: 7
- JSON starts with array bracket: True
- JSON ends with array bracket: True
- Duplicate CSV IDs: 0
- Duplicate JSON IDs: 0
- Added IDs missing from CSV: 0
- Added IDs missing from JSON: 0
- CSV IDs missing from JSON: 0
- JSON IDs missing from CSV: 0
- Blank required rows: 0
- Netlify marker: True
- Form marker: True
- Submit marker: True

## Added records

- MOC-0031 | 2026-06-15 | Proteus Fund / RISE Together — 2026 Small Grants Fund | 
- MOC-0034 | 2026-06-15 | IOM — Consultant, Legal Identity and Civil Registration Toolbox | 
- MOC-0043 | 2026-06-15 | OHCHR — Reconstruction and Internally Displaced Persons | 
- MOC-0028 | 2026-06-16 | FCDO — Uganda Refugee Support, Empowerment and Transformation ReSET Project | 
- MOC-0026 | 2026-06-17 | ICMPD — Internship, Research Unit | 
- MOC-0035 | 2026-06-18 | IOM — Case Manager, Assisted Voluntary Return | 
- MOC-0027 | 2026-06-19 | ICMPD ENHANCER PRO — Start-Up Grant Scheme Türkiye | 

## File hashes

- C:\Users\danie\Migration_Opportunity_Calendar\outputs\publication_packages\migration_opportunity_calendar_MINI_UPDATE_DEPLOY_CANDIDATE_v1_2L2_FIX_20260612_160551\DEPLOY_CANDIDATE_FILE_HASHES_v1_2L2_FIX.csv

## Deployment rule

Deploy only this folder if visual review is approved:

$deployCandidate

Do not deploy the previous v1.2L folder because its manifest used the non-robust JSON count and says Clean=False.
