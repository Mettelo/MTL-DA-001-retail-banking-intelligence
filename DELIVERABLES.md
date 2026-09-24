# Project Deliverables

## Delivery Principle

The project team is responsible for choosing and defending the technical approach. The client has specified the required business outcomes rather than prescribing a step-by-step solution.

All final outputs must be traceable from this repository.

## D1 — Discovery & Data Assessment

**Format:** Markdown or PDF  
**Due:** End of Week 1

Must include source-table inventory, grain, key relationships, row-count and uniqueness checks, missing-data assessment, duplicate assessment, date-range assessment, anomalies, risks, assumptions and questions requiring business clarification.

**Acceptance criterion:** another analyst should be able to understand what each source table represents and where the major data risks are.

## D2 — Analytical Data Model

**Format:** SQL/Python plus model documentation  
**Due:** Initial version by end of Week 3

Must include preserved raw data, documented transformations, reusable customer/account/transaction analytical structures, documented join logic, handling of exclusions and exceptional values, and reproducible build steps.

**Acceptance criterion:** the model can be rebuilt from the raw source data without undocumented manual editing.

## D3 — KPI & Metric Catalogue

**Format:** Markdown/CSV/Excel  
**Due:** End of Week 3

For each KPI include metric name, business purpose, definition, source fields, calculation logic, grain, exclusions and limitations.

Likely metric families include customer activity, account activity, transaction value and volume, balance behaviour, lending portfolio, repayment outcome, card penetration, standing-order usage and regional distribution.

**Acceptance criterion:** two analysts using the documented definition should arrive at the same result.

## D4 — Analytical Findings

**Format:** Reproducible notebook/report/query outputs  
**Due:** End of Week 4

Provide evidence-led analysis addressing the agreed business questions. Findings should distinguish observation, interpretation, uncertainty and recommendation.

**Acceptance criterion:** every material conclusion can be traced to data and reproducible analysis.

## D5 — Management Dashboard / Decision-Support Product

**Format:** Power BI, Tableau, Looker Studio or another justified solution  
**Due:** Draft by Week 5; final by Week 6

The product should provide a clear management view of agreed areas of customer and portfolio performance. It should not become a collection of unrelated charts.

**Acceptance criterion:** a senior stakeholder should be able to identify key performance patterns and drill into relevant areas without understanding the underlying code.

## D6 — Technical Handover Pack

**Format:** Repository documentation  
**Due:** Week 6

Must explain source data, project structure, transformation process, model design, metric definitions, assumptions, known limitations, reproduction steps and extension guidance.

**Acceptance criterion:** another analyst can continue the work without undocumented knowledge held by the original team.

## D7 — Executive Briefing

**Format:** Maximum 2 pages or equivalent concise briefing  
**Due:** Week 6

Cover the most important findings, business implications, major data risks, recommended management actions and recommended next-phase analytical work.

## D8 — Final Presentation

**Format:** 15–20 minute team presentation plus Q&A  
**Due:** Mettelo Demo Day

All team members should contribute. The panel may challenge definitions, assumptions, technical choices, data quality, conclusions, recommendations and limitations.

## Submission Location

The GitHub repository is the primary submission and evidence location.

Use:

- `/docs` for documentation;
- `/sql` for SQL;
- `/notebooks` for notebooks;
- `/src` for reusable code;
- `/deliverables` for final outputs or links to approved large files.

Large BI files, recordings or other binaries may be stored in an approved Mettelo Google Drive folder and linked from `/deliverables`.

**Do not submit the project by email.**

## Completion Gate

The project is complete only when all required deliverables have been submitted, repository documentation is complete, contribution evidence is visible, final outputs are reproducible, the final presentation has been delivered, and the Mettelo review panel has completed its review.
