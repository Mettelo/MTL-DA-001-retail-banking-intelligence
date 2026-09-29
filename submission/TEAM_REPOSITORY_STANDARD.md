# Mandatory Team Repository Standard

Each approved team must create its **own GitHub repository** for MTL-DA-001.

The team's repository is the official project submission.

## 1. Repository Name

Use:

```text
MTL-DA-001-<team-name>
```

Example:

```text
MTL-DA-001-north-star-analytics
```

Use lowercase for the team-name portion and hyphens instead of spaces.

## 2. Repository Visibility

The repository may remain **private during delivery**.

If private, the Team Lead must add the designated Mettelo reviewer GitHub account as a collaborator before submission.

Do not make the repository public unless the team has checked the data source terms, project rules and Mettelo publication requirements.

## 3. Mandatory Repository Structure

Every team repository must contain:

```text
MTL-DA-001-<team-name>/
│
├── README.md
├── CONTRIBUTIONS.md
├── requirements.txt              # if Python is used
├── .gitignore
│
├── data/
│   ├── README.md
│   ├── raw/
│   └── processed/
│
├── docs/
│   ├── 01-discovery/
│   ├── 02-data-model/
│   ├── 03-kpi-catalogue/
│   ├── 04-risk-and-limitations/
│   └── 05-technical-handover/
│
├── sql/
├── src/
├── notebooks/
├── analysis/
│
├── dashboard/
│   └── README.md
│
├── deliverables/
│   ├── executive-briefing/
│   └── presentation/
│
└── submission/
    └── FINAL_SUBMISSION.md
```

Folders that are not technically required may contain a `README.md` explaining why they were not used.

## 4. README Requirements

The repository-level `README.md` must contain:

- Project ID and title;
- team name;
- team members and roles;
- short business-problem summary;
- solution overview;
- architecture/data-flow summary;
- reproduction instructions;
- dashboard/output links;
- final deliverable links;
- known limitations;
- source-data attribution.

A reviewer should be able to understand the project without searching through the entire repository.

## 5. Git Workflow

Minimum expectations:

- meaningful commits;
- issues for significant tasks;
- branches for substantial changes;
- pull requests for material merges where practical;
- peer review for important code/model changes;
- no single final bulk upload by one person.

Suggested branch names:

```text
feature/<description>
analysis/<description>
data/<description>
docs/<description>
fix/<description>
```

## 6. File Naming

Use meaningful names.

Good:

```text
customer_activity_model.sql
loan_portfolio_analysis.ipynb
kpi_catalogue.md
data_quality_report.md
executive_briefing.pdf
```

Avoid:

```text
final.ipynb
final2.ipynb
newfinal.pbix
test123.csv
document1.pdf
```

## 7. Large Files

Large BI files, videos or generated artefacts may be stored in approved shared storage.

If stored externally, include the link in:

- `dashboard/README.md`; and
- `submission/FINAL_SUBMISSION.md`.

## 8. Reproducibility

Where relevant include:

- environment requirements;
- dependency file;
- SQL execution order;
- notebook order;
- transformation instructions;
- data download instructions;
- dashboard refresh instructions.

## 9. Contribution Evidence

`CONTRIBUTIONS.md` must record each person's actual contribution.

Mettelo may compare this record with commits, issues, pull requests, reviews, documentation, analytical artefacts and presentation evidence.

Commit count alone is not sufficient proof of contribution.


## Mandatory Mettelo Access

Every team delivery repository **must grant Mettelo access** for review, verification and project-quality assurance.

### If the repository is owned by a team member or another organisation

The Team Lead must invite the **designated Mettelo reviewer GitHub account** as a collaborator.

### If the repository is created inside the Mettelo GitHub organisation

The required Mettelo reviewer/team access must be retained.

### Submission rule

A repository will **not be treated as a complete Mettelo submission until Mettelo access has been granted and verified**.

The Team Lead is responsible for ensuring that:

- the invitation has been sent;
- the designated Mettelo reviewer can open the repository;
- the reviewer can inspect code, documentation, issues, pull requests and contribution history;
- access remains available throughout review and verification.

Do not remove Mettelo access until the project review and verification process is complete.



## Mandatory Mettelo Repository Access

Every team delivery repository must grant Mettelo access before the submission is considered complete.

### Exact GitHub account to invite

Invite this GitHub username:

```text
OlaoluwajohnsonT
```

### How to add Mettelo

If your repository is owned by a team member or another organisation:

1. Open your team repository on GitHub.
2. Select **Settings**.
3. Open **Collaborators** or **Collaborators and teams**.
4. Select **Add people**.
5. Search for the username **OlaoluwajohnsonT**.
6. Select the matching GitHub account.
7. Send the invitation.
8. Confirm the invitation has been sent successfully.

If the repository is already hosted inside the Mettelo GitHub organisation, do not remove existing Mettelo access.

### Required access before submission

Mettelo must be able to review:

- repository files and folders;
- commit history;
- branches;
- issues;
- pull requests;
- contribution evidence;
- final deliverables.

### Submission rule

A repository is **not a complete Mettelo submission until access for `OlaoluwajohnsonT` has been granted and verified**.

The Team Lead is responsible for confirming access and must keep it active until the review and verification process is complete.



## Mandatory Mettelo Organisation Access

Every team delivery repository must be accessible to the **Mettelo GitHub organisation** for review, verification and quality assurance.

### Preferred method — create the repository inside Mettelo

Where available, teams should create their delivery repository **inside the Mettelo GitHub organisation**.

This is the preferred setup because Mettelo can manage organisation-level access, teams and repository permissions centrally.

The repository name must follow:

```text
MTL-DA-XXX-<team-name>
```

### If your repository is created outside Mettelo

GitHub does not normally allow a personal repository to invite an entire organisation as a collaborator.

If your team creates the repository under a personal GitHub account or another organisation, you must follow the Mettelo access method communicated for that cohort before submission. This may require:

- transferring the repository into the Mettelo organisation; or
- granting access to the specific Mettelo reviewer account/team designated by Mettelo.

### Submission rule

A repository is **not a complete Mettelo submission until the Mettelo organisation has verified access**.

Mettelo must be able to review:

- repository files and folders;
- commit history;
- branches;
- issues;
- pull requests;
- contribution evidence;
- final deliverables.

Access must remain active until project review and verification are complete.

