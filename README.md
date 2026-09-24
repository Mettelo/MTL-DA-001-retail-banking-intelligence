# MTL-DA-001 — Retail Banking Customer & Portfolio Intelligence

**Mettelo Project Studio**  
**Project ID:** MTL-DA-001  
**Client:** Confidential Retail Banking Client  
**Sector:** Retail Banking & Financial Services  
**Engagement Type:** Simulated client engagement  
**Status:** Pre-launch  
**Team Size:** 5  
**Delivery Window:** 6 weeks  
**Repository:** Private

> **Confidentiality Notice**  
> The client name is intentionally withheld throughout this project. The organisation described in the brief is a simulated client created for Mettelo Project Studio using real anonymised banking data. Participants must treat the project materials as confidential and must not present the simulated client as a real external Mettelo customer.

## Engagement Summary

The client is a mid-sized retail banking organisation with several years of customer, account, transaction, standing-order, lending, card and regional data.

Senior management currently receives fragmented reporting from Commercial, Lending, Finance and Operations. Different teams use different definitions for active customers, account activity, loan performance and portfolio health. There is no single analytical view that connects customer behaviour, cash movement, product usage and lending outcomes.

Mettelo has formed a five-person project team to investigate the source data, establish defensible metrics, build a reproducible analytical layer and produce decision-support outputs for senior stakeholders.

This is not a dashboard-only exercise. The team is expected to work as an analytics delivery team: understand the business problem, assess the data, agree definitions, build the analytical layer, investigate material patterns, communicate risks and present recommendations.

## Primary Business Questions

1. What does the active customer and account base look like?
2. How do transaction behaviour and balances vary across customer groups and regions?
3. Which accounts or customer segments show materially different patterns of activity?
4. What does the lending portfolio look like and where are performance concerns concentrated?
5. How do standing orders, card ownership and transaction behaviour relate to wider customer engagement?
6. Which metrics should leadership monitor consistently going forward?
7. What data-quality or governance issues could cause management reporting to be misleading?

## Required Reading

1. [PROJECT_BRIEF.md](PROJECT_BRIEF.md)
2. [BUSINESS_CONTEXT.md](BUSINESS_CONTEXT.md)
3. [DELIVERABLES.md](DELIVERABLES.md)
4. [CONTRIBUTING.md](CONTRIBUTING.md)
5. [GOVERNANCE.md](GOVERNANCE.md)
6. [data/README.md](data/README.md)
7. [submissions/README.md](submissions/README.md)

## Source Data

The project uses the PKDD'99 Financial dataset, a real anonymised relational banking dataset. Mettelo uses it as source material for the simulated confidential-client engagement.

See [data/README.md](data/README.md) for the verified source, download instructions and handling rules.

## Repository Structure

```text
.
├── README.md
├── PROJECT_BRIEF.md
├── BUSINESS_CONTEXT.md
├── DELIVERABLES.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
├── data/
├── docs/
├── notebooks/
├── sql/
├── src/
├── deliverables/
└── submissions/
    ├── team-01/
    └── team-02/
```

## Delivery Rules

- GitHub is the primary technical workspace and evidence trail.
- Meaningful work should be linked to issues, commits, pull requests or documented artefacts.
- Raw source data must not be modified in place.
- Important analytical decisions and assumptions must be documented.
- Final outputs must be reproducible and understandable by another analyst.
- Email is not the primary project submission mechanism.
