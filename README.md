# GRIDCO Power Intelligence (prototype)

Clickable prototype of GNA Energy's proposed power purchase platform for GRIDCO, running entirely on illustrative data.

Modules:

- **Overview**: tomorrow's position, open payables, payment calendar, cost trend, data feeds
- **Data hub**: lineage map, sources, validation issues, master data, import log
- **Portfolio (EPM)**: day-ahead least-cost procurement with scenarios, merit order per hour, 12-month outlook, DSM
- **Billing**: bill reconciliation against contract version, schedules and meters; maker–checker approval; rebate and LPS deadlines
- **Regulations & contracts**: version-aware document library
- **Assistant**: answers with cited clauses and data records
- **Approvals**: role queues and audit trail

A single static `index.html` with no build step. Actions are stored in the browser's localStorage; use "Reset demo" in the sidebar to restore the seed data.

All figures, suppliers and clause wording are illustrative and are not actual GRIDCO records.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

```bash
npx vercel --prod
```
