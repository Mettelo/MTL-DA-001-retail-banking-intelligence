# Project Brief

## Engagement Details

| Field | Detail |
|---|---|
| Project ID | MTL-DA-001 |
| Project Title | Retail Banking Customer & Portfolio Intelligence |
| Client | Confidential Retail Banking Client |
| Sector | Retail Banking & Financial Services |
| Engagement | Simulated Mettelo Project Studio client engagement |
| Duration | 6 weeks |
| Team Size | 5 |
| Primary Sponsor | Director of Customer & Commercial Performance |
| Senior Stakeholders | Head of Lending, Head of Operations, Finance Business Partner, Data & Analytics Lead |

## Confidentiality

The client organisation name has been withheld intentionally.

For the purposes of the project, participants should work as though they have been engaged by a confidential retail banking client. However, this is a simulated Mettelo Project Studio engagement and must not be represented externally as paid employment or a real external Mettelo banking client.

The underlying source data is real anonymised banking data from a historical public research dataset.

## 1. Client Situation

The client has grown its customer and lending portfolio over several years. During that period, individual departments created their own spreadsheets and reporting processes to answer operational and management questions.

Commercial teams focus on customer activity and product usage. Lending teams monitor loans and repayment outcomes. Operations teams monitor transaction behaviour and account activity. Finance teams monitor balances, cash movements and portfolio-level performance.

These reports were never designed as one governed reporting system.

As a result:

- senior stakeholders receive different figures for apparently similar metrics;
- account-level and customer-level measures are sometimes mixed;
- repeat and inactive customers are not consistently defined;
- loan performance is viewed separately from wider account behaviour;
- regional and demographic information is not consistently incorporated;
- data-quality concerns are handled manually;
- management reporting depends heavily on spreadsheet interpretation.

The executive team has requested an analytical review before agreeing the next phase of reporting investment.

## 2. Business Problem

The client does not currently have a trusted, reproducible analytical view linking:

- customers;
- account ownership and permissions;
- transactions;
- standing orders;
- loans;
- cards;
- geographical and demographic context.

The project team has therefore been asked to create a structured analytical solution that gives management a clearer understanding of customer behaviour and portfolio performance.

The team must not assume that existing business definitions are correct. Where definitions are ambiguous, the team should identify the ambiguity, propose a defensible definition and document the impact.

## 3. Project Objectives

### A. Establish a trusted analytical foundation
Profile the supplied source data, identify the grain of each table, understand entity relationships and document material data-quality limitations.

### B. Create a reusable analytical layer
Develop a reproducible data model that supports customer, account, transaction and lending analysis without changing the raw source data.

### C. Standardise management metrics
Create and document a practical KPI framework covering customer activity, account behaviour, transaction activity and lending performance.

### D. Identify material portfolio patterns
Use evidence to identify meaningful differences across customers, accounts, regions, product usage and lending outcomes.

### E. Produce decision-support outputs
Provide senior stakeholders with an analytical product and management briefing that allow them to understand what is happening, where attention may be required and which questions require further investigation.

## 4. Key Business Questions

1. How large is the active customer and account base, and how should "active" be defined?
2. What are the major patterns in account balances and transaction activity?
3. Which customer or account groups demonstrate materially different behaviour?
4. How does activity vary across regions or demographic areas?
5. What does the lending portfolio look like by volume, value, repayment status and customer characteristics?
6. Are there behavioural patterns associated with weaker loan outcomes that warrant further investigation?
7. How widely are cards and standing orders used across the customer base?
8. Where could inconsistent definitions or poor-quality data distort management reporting?
9. Which KPIs should management monitor routinely?
10. What additional data would materially improve the quality of future analysis?

## 5. Expected Analytical Work

The project team is expected to:

- inspect and profile all relevant source tables;
- map primary and foreign-key relationships;
- distinguish customer-level, account-level and transaction-level grain;
- create documented transformation logic;
- define analytical populations and exclusions;
- investigate missing, inconsistent or unusual values;
- create reusable measures;
- perform exploratory and diagnostic analysis;
- identify findings that are decision-relevant;
- communicate uncertainty and limitations clearly;
- build a stakeholder-facing reporting product;
- maintain project documentation and version control throughout.

The project brief deliberately does not prescribe the exact technical solution.

## 6. Constraints

- no production banking system is available;
- no personally identifiable customer information is available;
- the historical source dataset must not be presented as current customer data;
- raw data must remain unchanged;
- material analytical logic must be reproducible;
- final recommendations must be supported by evidence;
- the team must distinguish observation from causal explanation;
- all major metric definitions and assumptions must be documented.

## 7. Success Criteria

The engagement will be considered successful if the team can demonstrate that:

- the supplied data has been understood and modelled correctly;
- important data-quality issues have been identified;
- customer, account and transaction grain have not been confused;
- management metrics are clearly defined;
- the analytical product can be reproduced;
- findings are traceable to evidence;
- recommendations are appropriately qualified;
- technical documentation is sufficient for handover;
- the team can defend its decisions during the final review.

## 8. Out of Scope

- deployment to a live bank environment;
- automated customer credit decisions;
- contacting or identifying real individuals;
- regulatory compliance certification;
- production fraud detection;
- redesigning the client's core banking system;
- representing the simulated client as a real external Mettelo customer.

## 9. Final Review

At the end of week 6, the team will present its solution to a Mettelo review panel acting as the client's senior stakeholder group.

The team should be prepared to explain:

- what was built;
- why particular definitions and modelling choices were made;
- what the most important findings are;
- which findings management should act on;
- what cannot be concluded from the available data;
- what should happen next.
