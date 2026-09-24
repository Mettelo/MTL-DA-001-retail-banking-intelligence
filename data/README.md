# Data Workspace — MTL-DA-001

This folder contains the source-data guidance for **Retail Banking Customer & Portfolio Intelligence**.

## Folder Structure

```text
data/
├── README.md
├── raw/
├── reference/
└── metadata/
```

## Dataset

**PKDD'99 Financial Dataset (Berka Financial Dataset)**

This project uses a real anonymised relational banking dataset originally released for the PKDD'99 Discovery Challenge.

The dataset includes approximately:

- 5,369 clients;
- 4,500 accounts;
- 8 core relational tables;
- transaction histories;
- loans;
- standing orders;
- cards;
- demographic/district information.

## Expected Raw Files

- `account.asc`
- `client.asc`
- `disp.asc`
- `trans.asc`
- `order.asc`
- `loan.asc`
- `card.asc`
- `district.asc`

## Official / Reference Source

CTU Prague Relational Learning Repository:

https://relational.fel.cvut.cz/dataset/Financial

## Public Mirror

https://github.com/jlacko/berka-dataset

Direct ZIP:

https://github.com/jlacko/berka-dataset/archive/refs/heads/master.zip

## raw/

Use `data/raw/` for the original source files.

Do not manually edit the raw files.

## reference/

Use `data/reference/` for:

- original dataset documentation;
- value/code interpretation notes;
- approved lookup/reference material;
- licence/source notes.

## metadata/

Use `data/metadata/` for:

- provenance notes;
- file inventory;
- schema documentation;
- data dictionary;
- known limitations;
- download/extraction notes.

## Project Framing

For the Mettelo engagement, the source files represent extracts supplied for analysis by the **Confidential Retail Banking Client**.

The original public-source provenance must still be documented internally.

Participants must not imply that the historical public dataset is current confidential data from a real Mettelo client.

## Team Repository Rule

Each team should mirror the same principles in its own repository:

```text
data/
├── README.md
├── raw/
└── processed/
```

Raw data must remain unchanged. Processed datasets should be reproducible from code or documented transformations.
