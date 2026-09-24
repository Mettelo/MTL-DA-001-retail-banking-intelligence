# Source Data — MTL-DA-001

## Dataset Selected

**PKDD'99 Financial Dataset (Berka Financial Dataset)**

This project uses a real anonymised relational banking dataset originally released for the PKDD'99 Discovery Challenge.

The dataset represents banking operations across multiple linked tables rather than a single classroom-style CSV.

It includes approximately:

- 5,369 clients;
- 4,500 accounts;
- 8 core relational tables;
- transaction histories;
- loans;
- standing orders;
- cards;
- demographic/district information.

## Core Tables

| File | Business Meaning |
|---|---|
| `account.asc` | Bank account records |
| `client.asc` | Client/customer records |
| `disp.asc` | Relationship/permission between client and account |
| `trans.asc` | Account transactions |
| `order.asc` | Permanent/standing payment orders |
| `loan.asc` | Loans associated with accounts |
| `card.asc` | Payment-card records |
| `district.asc` | District-level demographic/economic information |

## Verified Reference Source

CTU Prague Relational Learning Repository:

https://relational.fel.cvut.cz/dataset/Financial

## Download Source

Public mirror of the original source files:

https://github.com/jlacko/berka-dataset

Direct ZIP download:

https://github.com/jlacko/berka-dataset/archive/refs/heads/master.zip

The mirror contains the original `.asc` files and the accompanying data-description document.

## Project Framing

Participants should not build the project around the historical public-dataset name.

For Mettelo delivery purposes, these source files represent extracts supplied by the **Confidential Retail Banking Client**.

The source provenance remains documented internally, and participants must not imply that the historical public data came from a real current Mettelo client.

## Data Handling

- Do not manually edit the raw files.
- Keep raw and transformed data separate.
- Generate derived datasets reproducibly using SQL, Python or another documented process.
- Avoid committing unnecessarily large generated datasets.
- Keep code, data dictionaries, transformation logic and documentation in GitHub.

## Expected Data Work

Participants are expected to:

- investigate coded fields;
- validate relationships;
- profile missing and exceptional values;
- distinguish customers from accounts;
- understand the client-account disposition relationship;
- document translations and derived fields;
- preserve original values in the raw layer.

## Project Rule

Do not search for or reuse pre-built solutions, notebooks or dashboards based on this dataset.

The objective is to reproduce realistic project delivery, not replicate an existing public analysis.

Any external reference used for field interpretation must be documented.
