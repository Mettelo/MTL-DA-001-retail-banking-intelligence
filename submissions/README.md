# Mettelo Team Submissions

This folder is the official final-submission area for **MTL-DA-001 — Retail Banking Customer & Portfolio Intelligence**.

There is **no fixed number of teams**.

Any approved project team can submit by creating its own team folder inside `/submissions`.

---

## 1. Create Your Team Submission Folder

The Team Lead should create one new folder directly inside:

```text
/submissions
```

Use this naming format:

```text
<team-name>/
```

Examples:

```text
submissions/
├── data-navigators/
├── insight-forge/
├── northstar-analytics/
└── quant-collective/
```

### Folder-Naming Rules

Your team folder name must:

- be unique within this project;
- use lowercase letters;
- use hyphens instead of spaces;
- avoid personal email addresses or phone numbers;
- avoid offensive or misleading names;
- not use `mettelo`, `admin`, `official`, or another name that could imply Mettelo ownership unless authorised.

Example:

`North Star Analytics` → `north-star-analytics`

---

## 2. Required Folder Structure

Inside your team folder, create:

```text
submissions/
└── your-team-name/
    ├── FINAL_SUBMISSION.md
    ├── executive-briefing/
    ├── presentation/
    ├── technical-handover/
    └── links/
```

You may add other folders where genuinely needed, but keep the structure understandable.

---

## 3. Prepare FINAL_SUBMISSION.md

Copy:

```text
/submissions/FINAL_SUBMISSION_TEMPLATE.md
```

into your team folder and rename the copy:

```text
FINAL_SUBMISSION.md
```

Complete every relevant section.

This file is the official index of your final submission.

It should link to:

- your dashboard;
- final executive briefing;
- technical documentation;
- presentation;
- large files stored externally;
- key pull requests;
- key GitHub issues;
- contribution evidence.

---

## 4. Where Different Deliverables Should Go

### GitHub

Use GitHub for:

- SQL;
- Python;
- notebooks;
- documentation;
- data models;
- KPI definitions;
- analytical outputs that are suitable for version control;
- final submission record;
- contribution history.

### Mettelo-approved shared storage

Use the approved shared storage location for:

- large `.pbix` files;
- Tableau workbooks where required;
- large exports;
- video recordings;
- files that exceed practical GitHub limits.

Add the link to those files inside `FINAL_SUBMISSION.md`.

### Do Not Submit By Email

Email is not an accepted final-submission location.

---

## 5. Recommended GitHub Workflow

Each team should complete its work on its own working branch.

Recommended branch-name format:

```text
team/<team-name>
```

Example:

```text
team/north-star-analytics
```

The team should:

1. create or work from its team branch;
2. use issues to track meaningful work;
3. commit work regularly;
4. use pull requests for major internal changes where practical;
5. prepare the final submission inside its own folder;
6. open one final Pull Request to Mettelo for review.

---

## 6. Final Pull Request

When your submission is complete, the Team Lead should open a Pull Request to the project review branch specified by Mettelo.

Use this PR-title format:

```text
MTL-DA-001 | <Team Name> | Final Submission
```

Example:

```text
MTL-DA-001 | North Star Analytics | Final Submission
```

The Pull Request description should include:

- team name;
- Team Lead;
- link to `FINAL_SUBMISSION.md`;
- confirmation that all required deliverables are included;
- confirmation that all external links are accessible to Mettelo reviewers;
- any unresolved limitation or known issue.

Do not merge the Pull Request yourself unless Mettelo explicitly asks you to.

---

## 7. What Mettelo Will Review

Mettelo may review:

- completeness of the submission;
- reproducibility;
- repository structure;
- data-quality work;
- metric definitions;
- analytical reasoning;
- dashboard quality;
- technical documentation;
- executive communication;
- GitHub issues and pull requests;
- contribution evidence for individual team members;
- final presentation performance.

---

## 8. Individual Contribution Evidence

Every participant should have visible evidence of their contribution.

Evidence may include:

- commits;
- pull requests;
- issue ownership;
- code review;
- analytical documentation;
- model development;
- dashboard development;
- project-management artefacts;
- presentation sections.

Commit count alone does not prove contribution quality.

---

## 9. Submission Checklist

Before opening the final Pull Request, confirm that:

- [ ] your team has created a uniquely named folder under `/submissions`;
- [ ] `FINAL_SUBMISSION.md` is complete;
- [ ] all required deliverables are included or linked;
- [ ] external links work for Mettelo reviewers;
- [ ] technical work is reproducible;
- [ ] assumptions and limitations are documented;
- [ ] each team member's contribution is recorded;
- [ ] no other team's folder has been modified;
- [ ] the team has not submitted by email;
- [ ] the Team Lead has reviewed the complete submission.

---

## Important

Do not edit or delete another team's submission folder.

Do not copy another team's solution.

Teams may be working on the same client problem, but each team must produce and defend its own analytical approach.
