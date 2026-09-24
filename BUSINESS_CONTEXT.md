# Business Context

## Client Profile

**Client Name:** Confidential  
**Sector:** Retail Banking & Financial Services  
**Operating Model:** Multi-region retail banking  
**Engagement Type:** Simulated Mettelo Project Studio engagement

The client serves individual banking customers across multiple districts and maintains transactional accounts, payment instructions, lending products and payment cards.

The organisation's identity is intentionally withheld within the project pack to reproduce the working conditions of a confidential client engagement.

## Why the Engagement Was Commissioned

The executive team has become increasingly concerned that different functions are presenting different versions of customer and portfolio performance.

A recent management review highlighted three recurring problems:

1. teams use different definitions for basic measures such as active account and active customer;
2. lending information is reviewed separately from wider account behaviour;
3. analysts spend significant time reconciling spreadsheet reports before meetings.

Management does not yet want a major technology implementation. It first wants an evidence-led assessment of the available data and a prototype analytical solution showing what a governed reporting approach could look like.

## Stakeholders

### Director of Customer & Commercial Performance — Project Sponsor
Needs a reliable view of customer activity, engagement patterns, regional differences and opportunities for deeper customer analysis.

### Head of Lending
Needs visibility of loan portfolio composition, repayment outcomes and characteristics associated with weaker performance.

### Head of Operations
Needs to understand transaction volumes, account behaviour, standing orders and operational patterns that may require attention.

### Finance Business Partner
Needs confidence that reported measures are traceable, consistently defined and do not double-count customers, accounts or transactions.

### Data & Analytics Lead
Needs the work to be reproducible, documented and capable of being handed over to another analyst.

## Current-State Reporting

The current environment is assumed to include:

- spreadsheet-based management reports;
- manually reconciled figures;
- separate functional extracts;
- inconsistent metric definitions;
- limited shared documentation;
- no agreed analytical model spanning customers, accounts, transactions and loans.

## Decision Context

The executive team is considering whether to invest in a more formal management-information and analytics capability.

The project findings will therefore be used to help answer:

- whether the available data can support reliable management reporting;
- which metrics are sufficiently robust to operationalise;
- where data-quality remediation is required;
- which analytical areas offer the strongest business value;
- what additional data or system improvements should be prioritised.

## Analytical Challenge

The source system is relational. Different tables operate at different levels of granularity.

Examples include:

- one customer may be connected to an account through a disposition/permission relationship;
- an account may have many transactions;
- an account may have multiple standing orders;
- card records relate to account permissions rather than directly to every transaction;
- loans relate to accounts;
- district information provides contextual demographic information.

Participants must therefore validate relationships rather than rely on simple flat-table joins.

## Confidentiality Position

The client identity and selected contextual details are withheld as part of the Mettelo Project Studio simulation.

Participants may describe verified work as a Mettelo Project Studio engagement, but must not claim that the confidential client is a real external Mettelo banking customer.
