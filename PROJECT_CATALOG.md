# Project catalog — Okum Udeh

Reviewed 8 November 2026. This catalog covers recoverable completed artifacts and existing GitHub projects. It does not claim access to every historical conversation or certify course submission.

## Taxi Driver and Flappy Birds

**Completed playable implementations.** [Download package](01-python-games.zip)

Two Pygame games with source code, controls, rule tests and scripted demo screenshots.

**Evidence:** Reran all 5 bundled unit tests on 8 November 2026: PASS (Python 3.12, Pygame 2.6.1, dummy video/audio drivers).

**Limitations:** Bundled images are scripted headless renders, not photographs of the student’s Ubuntu desktop. These are playable games, not trained reinforcement-learning agents. No submission status is inferred.

## Skyline Air flight performance

**Completed Excel capstone.** [Download package](02-skyline-air.zip)

Fictional-airline analysis of 1,012 raw records, 12 exact duplicates and 1,000 unique flights. Arrival OTP: 703/957 (73.46%); departure OTP: 728/973 (74.82%).

**Evidence:** Reran supplied read-only validator on 8 November 2026: PASS. It checks counts, ordering, KPI reconciliation, 2 PivotTables, 4 slicer caches and no cached Excel errors.

**Limitations:** Validator does not recalculate Excel or exercise live slicer clicks. Dashboard dropdowns are separate from Native_Pivots slicers. Original video is a captioned reconstruction, not a contemporaneous build recording. Source case is fictional. Original documents remain historical snapshots.

## AOL and GeoNames Exasol BI group project

**Completed analysis and reporting; separate later export documented.** [Download package](03-exasol-bi.zip)

Group attribution: Michael, Okum and Phillip. SQL, geographic reference data, aggregate outputs and charts from the Exasol project. The November 3 question-3 report is retained as a separate result version.

**Evidence:** Recovered handoff records actual DataGrip/Exasol execution by the student. This archival pass did not reconnect to the course database. The October ZIP cohort reports 18,697 events and 5,117 clicks (27.37%).

**Limitations:** Modern ZIP lookup does not identify users’ residences. October pipeline and November question-3 export have different populations and must not be combined. November report uses 1,190,929 events and summed state-user counts of 7,154, not globally distinct people. Star schema is a logical model; physical deployment and data-product canvas are not verified. Original desktop photos and user-level session exports are omitted.

## AOL search journeys

**Completed local analysis; Exasol port unverified.** [Download package](04-aol-search-journeys.zip)

Local DuckDB analysis of the 2006 AOL release, with aggregate reports, SQL, Python scripts and charts.

**Evidence:** Recovered completed package reports 36,389,567 raw records, 35,389,190 retained rows, 28,037,812 proxy events and 10,493,991 sessions. Large-data analysis was not rerun during archiving.

**Limitations:** This standalone DuckDB variant differs from the group Exasol pipeline. Its Exasol scripts were not executed in the supplied record. Raw search histories are not included; source data can contain sensitive historical searches. Aggregates do not establish intent or residence.

## US state search-interest analysis

**Completed local analysis; Exasol port unverified.** [Download package](05-us-state-mentions.zip)

State-name mention analysis with population normalization, scripts, SQL, charts, report and presentation.

**Evidence:** Recovered results document 28,037,812 cleaned events, 1,132,545 state-mention events and 1,137,864 event-state pairs. Saved report gives population correlation 0.8093. Not rerun over raw logs in this archival pass.

**Limitations:** A search can mention several states. Mentioned states are not residences. This is distinct from ZIP matching and from the later Exasol question-3 export. Exasol deployment remains unverified.

## US postal data for Excel and MySQL

**Completed conversion; database import unverified.** [Download package](06-us-postal-conversion.zip)

A 41,490-row, 12-field GeoNames export converted to Excel, CSV and a MySQL creation/import script.

**Evidence:** Recovered package includes all three formats and original GeoNames readme. No successful MySQL execution is claimed.

**Limitations:** This source preserves duplicate ZIP codes; postal code alone is not a unique key. It differs from the 40,977-row cleaned lookup used in the Exasol project. Read READ_ME.txt before import; do not repeat inserts blindly.

## QuickDash delivery performance

**Completed spreadsheet analysis.** [Download package](07-quickdash.zip)

Delivery-fee analysis with a cleaned delivery sheet, analysis sheet and Lagos filter.

**Evidence:** Inspected saved workbook values: 109 deliveries, 95 ratings, total fees ₦380,640, average ₦3,492.11, median ₦3,740, Lagos fees ₦71,320.

**Limitations:** The original workbook contains named riders and payment-related delivery records. Only a documentation summary is archived here because the source’s synthetic/public status is unconfirmed; original workbook remains in ChatGPT. Cached results were inspected, not independently recalculated.

## Bright Path recruitment data quality

**Completed workbook; documentation-only archive.** [Download package](08-bright-path.zip)

Spreadsheet cleaning and data-quality exercise involving 110 application records.

**Evidence:** Inspected workbook sheets: Summary, Cleaned Candidates, Raw Data, BranchLookup and Data Quality Log. Summary records 18 missing interview scores, 2 malformed IDs and 4 excess exact copies.

**Limitations:** Candidate records, contact details and screening outputs are not uploaded. The original workbook remains in ChatGPT. No new selection or employment decision was made. Record counts are not verified unique-person counts; assumed score ranges require confirmation.

## Data science learning guides

**Completed educational documents.** [Download package](09-learning-resources.zip)

Four completed guides: Mathematical Models (1–11), Statistics/R (six lessons), AI study lessons and Data Science Platforms.

**Evidence:** Four PDF artifacts recovered. These are learning materials, not evidence of passed exams or independently validated solutions.

**Limitations:** Source lecture decks and personal university records are not included. AI-assisted explanations may require checking against course material.

## Football fixtures and comparison workbooks

**Completed dated spreadsheet outputs.** [Download package](10-football-analysis.zip)

Representative workbooks from the recurring fixture, score-comparison and prediction-analysis work.

**Evidence:** Four completed dated workbooks recovered. Their analysis represents the date in each filename, not live schedules.

**Limitations:** Many daily variants were generated; this archive groups them as one project family rather than calling every date a new project. Predictions are not validated betting performance or guaranteed outcomes. No current fixture or profitability claims are made.

## Projects already on GitHub

| Project | Repository | Review scope |
|---|---|---|
| Ancient History RAG | [ancient-history-rag](https://github.com/blastudeh/ancient-history-rag) | Updated evaluation record; see RAG addendum below. |
| Python scaffold/calculator/factorization | [py-fun](https://github.com/blastudeh/py-fun) | Existing source, tests, docs and result logs observed; no new test run. |
| Python development container | [dev-container-python](https://github.com/blastudeh/dev-container-python) | Dockerfile and configuration observed; container rebuild not verified. |
| Portfolio websites | [okum-portfolio](https://github.com/blastudeh/okum-portfolio), [okumudeh.github.io](https://github.com/blastudeh/okumudeh.github.io), [okum-udeh-portfolio](https://github.com/blastudeh/okum-udeh-portfolio) | Existing site assets retained; deployment health not certified. |

## RAG addendum

The supplied 7 November 2026 llama3.2:1b run completed all 13 questions without recorded generation errors. Twelve questions called the model; one used deterministic no-evidence refusal. Source recall@4 was 1.0 for 10 answerable questions, which is not answer accuracy. Manual review identifies incorrect refusals, incomplete answers and citation issues. There is no fresh same-model 1B baseline comparison. The recovered Ubuntu code uses a 600-second timeout and an 80-word instruction; its 14 tests passed again on 8 November.

## Scope and exclusions

Personal medical, immigration, financial and family documents are excluded. Candidate and rider records are documentation-only. Raw AOL histories, individual session exports and desktop-photo collections are excluded. Earlier scaffold ZIPs superseded by completed packages are not presented as final projects. RapidMiner work and other conversation-only exercises lack a recovered completed workflow here and are not labelled finished. Original attribution and data-source notices remain in the packages. No broad license is imposed on third-party datasets.
