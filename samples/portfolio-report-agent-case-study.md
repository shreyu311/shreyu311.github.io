# Portfolio Report Agent — Case Study Outline

**Role:** Business Analysis · Reporting Automation · Portfolio Operations  
**Company:** Aosenuma.ai (co-op) · Jan–Jun 2026  
**Stack:** Notion Custom Agents, Projects Database, Open Tasks, Mermaid Gantt

---

## Problem

Every Monday, PMs manually rebuilt the same **Actuals vs Forecast** portfolio deck:

- Pulled dates, task counts, and status notes from multiple Notion databases
- Re-formatted Gantt views and executive summaries by hand
- ~**2.5 hours** of copy-paste per week across **7 active projects**
- Numbers sometimes conflicted between decks and source databases

## My role

- Defined reporting requirements and acceptance criteria with PM stakeholders
- Mapped canonical data sources (Projects DB, Open Tasks)
- Wrote agent instructions: reference reports = format only; live metrics = source DBs
- Configured weekly **Monday 8:00 AM** trigger
- Validated output against PM review checklist for four consecutive runs

## Solution

Notion custom agent produces each week:

1. Executive summary (7-project portfolio)
2. Forecast vs actual variance flags
3. Portfolio-level Gantt (Mermaid)
4. One project deep dive
5. Top portfolio risks and weekly action items

## Outcome

| Metric | Before | After |
|--------|--------|-------|
| Manual prep time | ~2.5 hrs/week | ~20 min review/week |
| Portfolio scope | 7 projects | 7 projects (automated) |
| Data integrity | Conflicting deck copies | Single canonical report |
| Schedule | Ad hoc | Every Monday 8 AM |

## Data flow (as-is → to-be)

```
[Before] PM → copy from DBs → paste into deck → email leadership
[After]  Trigger → Agent reads Projects DB + Tasks → generates report → PM reviews → publish
```

## Artifacts

- [Redacted sample report (PDF)](../samples/Portfolio_Actuals_vs_Forecast_June_2026_Redacted.pdf) — structural proof; client data removed

---

*Redacted for portfolio use. Methodology and structure preserved; sensitive client data removed.*
