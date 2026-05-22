# Customer Support Ticket Analytics BI

Business intelligence and dashboarding project focused on understanding customer support ticket patterns, service quality, SLA performance, and operational pressure points.

## Why I Built This

Support ticket data is useful for finding where customers struggle, where teams spend time, and where service processes can improve. This project was built to practise business intelligence, data quality review, and stakeholder-style reporting using Power BI, Tableau, Excel, and written analysis.

## Business Questions

- What is the status mix across support tickets?
- Which ticket priorities, topics, and source channels create the most demand?
- How often are first-response and resolution SLAs met or violated?
- Which support levels handle the largest share of work?
- What data-quality risks need to be considered before using the dashboard for decisions?

## Tools Used

Power BI, Tableau, Excel, dashboard design, data cleaning, KPI reporting, and business analysis.

## What I Implemented

I reviewed a customer support ticket dataset, explored service patterns, prepared dashboard-ready summaries, identified fields that should not be shared publicly, and created public-safe evidence for repository review. The original project also includes Power BI and Tableau dashboard files prepared locally.

## Repository Guide

| Path | Purpose |
|---|---|
| `data/` | Public-safe support ticket sample and dataset sharing notes. |
| `outputs/` | Dataset profile, SLA summaries, ticket status, priority, source, support level, and top-topic outputs. |
| `dashboards/` | Dashboard evidence notes for the Power BI and Tableau files. |
| `reports/` | Public report summary and analysis context. |
| `assets/` | Public-safe aggregate visuals for quick review. |
| `tool-requirements.md` | Tools used to build and review the project. |

## Public Evidence Added

- Public-safe sample support ticket data with ticket IDs, agent names, exact timestamps, and coordinates removed.
- Dataset profile covering 2,330 support tickets.
- Ticket status, priority, source, support level, and top-topic output files.
- First-response and resolution SLA output files.
- Report summary explaining the business value and analysis focus.
- Dashboard evidence guide explaining the Power BI and Tableau assets.
- Aggregate visuals for ticket status and SLA performance.

## Outputs And Results

The output shows a support operation where most tickets are closed or resolved, email is the largest support channel, product setup is the most common topic, and resolution SLA performance is weaker than first-response SLA performance. These are useful signals for support process review and dashboard storytelling.

## Project Walkthrough

A good way to explore this project is to start with `outputs/dashboard_output_summary.md`, then review the public sample in `data/`, the summary CSVs in `outputs/`, and the visual summaries in `assets/`. The project is designed to show practical BI thinking: clean data, clear operational questions, and dashboard-ready evidence.

## Public Sharing Note

The original Excel workbook, Power BI file, Tableau workbook, and reflection PDF are kept locally until each file is checked for embedded private fields. The public GitHub version uses safe summaries and samples so the project can be reviewed without exposing ticket-level identifiers.
