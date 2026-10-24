# Decathlon Tableau Project

Repository for the Tableau Intern Project Sprint, covering business requirements, data preparation, Tableau analysis, dashboard design, and quality assurance.

## Repository structure

```text
.
├── data/
├── docs/
├── tableau_workbook/
├── screenshots/
├── README.md
└── .gitignore
```

- `data/`: Data approved for sharing in this repository.
- `docs/`: Separate DAD, BRD, and FRD requirements documents; mockups; data dictionary; data-quality log; calculation register; QA checklist; and issue log.
- `tableau_workbook/`: Draft and final Tableau packaged workbooks (`.twbx`).
- `screenshots/`: Dashboard pages and key interactions.

Each folder contains a `.gitkeep` placeholder so Git can retain it while empty. Existing repository files are preserved.

## Project status

The folder structure and three separate requirements documents are prepared, based on the supplied `v12.twbx` and sprint brief:

- [DAD — Dataset Assessment Document](docs/Decathlon_DAD.pdf): four pages covering source tables, grains, relationships, data-quality controls, and assessment requirements.
- [BRD — Business Requirements Document](docs/Decathlon_BRD.pdf): five pages covering stakeholders, business questions, scope, KPI definitions, and success criteria.
- [FRD — Functional Requirements Document](docs/Decathlon_FRD.pdf): four pages covering dashboard behavior, filters, interactions, nonfunctional requirements, and acceptance tests.

Each PDF includes its own source details, evidence limits, validation status, and open decisions. These documents replace the combined requirements PDF.

Static inspection identified four dashboards, 27 worksheets, ten logical tables, nine relationships, and 21 calculated fields. The documents separate observed workbook configuration from proposed requirements and unrun checks. Dataset profiling, numeric KPI reconciliation, and Tableau runtime testing are still pending.

The source `v12.twbx` was supplied for documentation and is not included in this upload. The existing `.upload_tmp/chunk_001.b64` is an incomplete older transfer, not a usable packaged workbook. Final workbook delivery, screenshots, and publication remain pending.

## Portfolio documentation to complete

- Business problem, stakeholders, questions, and KPIs.
- Data source, granularity, preparation steps, and sharing restrictions.
- Tableau features and calculation definitions.
- Three to five evidence-based insights.
- Validation results, assumptions, and limitations.
- Final packaged workbook location and Tableau Public link, if published.

Store only data and workbooks approved for sharing. Packaged workbooks may contain embedded data. Temporary and local private files are excluded by `.gitignore`; these rules do not remove files already tracked by Git.
