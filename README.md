# AEI · Genotwin — Project Suite

Six self-contained artifacts. No build step, no backend. Host all files in one folder; `index.html` is the front door.

## Files

| File | What it is | Opened from |
|---|---|---|
| `index.html` | **Project Intro + Capgemini Decision Brief + Architecture Engine** (3 views in one: Intro / Boardroom / Engine, plus a 60-second brief) | the entry URL |
| `cockpit.html` | Genotwin Founder Cockpit — AEI applied to ourselves | Intro tile |
| `workbench.html` | AEI Workbench MVP — three companies, live simulators, clickable decisions | Intro tile + card |
| `architecture-sap.html` | Architecture Engine — SAP instance (standalone) | direct link |
| `board-briefing.html` | SAP Board Briefing Pack — the bound quarterly GTM artifact | Intro tile |
| `methodology.html` | AEI Score Methodology — the customer-neutral framework | Intro tile |

The Capgemini Architecture Engine and the Capgemini Decision Brief live **inside** `index.html` as views (no separate file needed).

## Deploy

**GitHub Pages:** create a repo, upload all files to the root, Settings → Pages → Deploy from branch → `main` / root. The entry URL serves `index.html`.

**Netlify / Vercel:** drag the folder onto the deploy target. Done.

## Note for sharing

Figures for SAP and Capgemini are **illustrative composites** — realistic but modelled, not live customer data. Frame as "what AEI surfaces when pointed at a firm like this," not live data.
