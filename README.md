# Audit Evidence & Compliance Tracker

An Excel-based tool for tracking audit evidence requests and mapping them to ISO 27001/27002 and
COBIT controls — built to understand how compliance/audit teams manage incoming requests from
intake through submission.

## What it does

- **Logs every audit request** — title, requesting team, control domain, control reference,
  evidence owner, dates, and status.
- **Auto-flags status** — a formula reads the due date and status you enter and classifies each
  request as Not Started, In Progress, Due Soon, Overdue, or Submitted, with conditional
  formatting so overdue items stand out immediately.
- **Live readiness dashboard** — total requests, completion rate, and breakdowns by status and by
  control domain, each with a chart, calculated automatically from the log.
- **Control-to-evidence reference** — 21 ISO 27001/27002 and COBIT controls mapped to the evidence
  artifact typically expected for each, so scoping a new request doesn't start from scratch.

Everything recalculates live — change due date or status on the log and the dashboard updates
on its own.

## Contents

- `Audit_Evidence_Compliance_Tracker.xlsx` — the workbook, with four tabs:
  - **Dashboard** — summary stats and charts
  - **Audit Request Log** — the request tracker with dropdowns and conditional formatting
  - **Control Reference** — the ISO 27001/27002 & COBIT control-to-evidence table
  - **Instructions** — how to use and extend it, including connecting it to Power BI

## How to use it

1. Open the workbook in Excel (or Google Sheets / LibreOffice Calc).
2. Log a new request in the **Audit Request Log** tab — pick the control domain and status from
   the dropdowns, the rest is typed in.
3. Check the **Dashboard** tab for a live view of where things stand.
4. Use the **Control Reference** tab when scoping a new request, to see what evidence is typically
   expected for a given control.

## Notes

- Request IDs AR-001 through AR-008 are sample data included to demonstrate the tracker — replace
  them with real requests, or clear them and start fresh.
- Control mappings reference public ISO 27001/27002 and COBIT control identifiers, not any
  organization's internal audit findings.
