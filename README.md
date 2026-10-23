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
- `docs/`: Combined DAD, BRD, and FRD requirements; mockups; data dictionary; data-quality log; calculation register; QA checklist; and issue log.
- `tableau_workbook/`: Draft and final Tableau packaged workbooks (`.twbx`).
- `screenshots/`: Dashboard pages and key interactions.

Each folder contains a `.gitkeep` placeholder so Git can retain it while empty. Existing repository files are preserved.

## Project status

The folder structure and [combined DAD, BRD, and FRD requirements document](docs/Decathlon_Combined_Requirements_DAD_BRD_FRD.pdf) are prepared. The nine-page PDF is based on the supplied `v12.twbx` and sprint brief. It covers the dataset model, business questions, KPI definitions, dashboard behavior, acceptance checks, and open decisions.

Static inspection identified four dashboards, 27 worksheets, ten logical tables, nine relationships, and 21 calculated fields. The document separates observed workbook configuration from proposed requirements and unrun checks. Dataset profiling, numeric KPI reconciliation, and Tableau runtime testing are still pending.

The source `v12.twbx` was supplied for documentation and is not included in this upload. The existing `.upload_tmp/chunk_001.b64` is an incomplete older transfer, not a usable packaged workbook. Final workbook delivery, screenshots, and publication remain pending.

## Portfolio documentation to complete

- Business problem, stakeholders, questions, and KPIs.
- Data source, granularity, preparation steps, and sharing restrictions.
- Tableau features and calculation definitions.
- Three to five evidence-based insights.
- Validation results, assumptions, and limitations.
- Final packaged workbook location and Tableau Public link, if published.

Store only data and workbooks approved for sharing. Packaged workbooks may contain embedded data. Temporary and local private files are excluded by `.gitignore`; these rules do not remove files already tracked by Git.
