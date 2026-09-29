# Team Submission Guide

## Overview

For MTL-DA-001, teams submit a **GitHub repository**, not a folder inside the Mettelo master repository and not an email attachment.

The team's repository should contain the complete evidence trail of the project.

## Step 1 — Agree Your Team Name

Choose a unique team name.

Example:

`North Star Analytics`

Repository-safe version:

`north-star-analytics`

## Step 2 — Create the Team Repository

Create:

```text
MTL-DA-001-north-star-analytics
```

One repository per team.

Do not create separate repositories for individual members.

## Step 3 — Add Team Members

The Team Lead should add all team members as collaborators with appropriate access.

Each participant should use their own GitHub account.

Do not share one GitHub login across the team.

## Step 4 — Invite Mettelo to Your Repository — Mandatory

Before your project can be submitted, your team must give Mettelo access to the delivery repository.

### GitHub username to invite

```text
OlaoluwajohnsonT
```

### Step-by-step

1. Open your team project repository on GitHub.
2. Click **Settings**.
3. Select **Collaborators** or **Collaborators and teams**.
4. Click **Add people**.
5. Search for **OlaoluwajohnsonT**.
6. Select the matching GitHub user.
7. Send the invitation.
8. Confirm the invitation appears as sent/pending or accepted.
9. Keep the access active until Mettelo completes review and verification.

### Important

Your submission is **not complete until Mettelo can access the repository**.

Mettelo must be able to inspect:

- project files;
- commit history;
- branches;
- issues;
- pull requests;
- contribution records;
- final deliverables.

If the repository is already inside the Mettelo GitHub organisation, retain the existing Mettelo access.

## Step 5 — Build the Required Structure

Follow [TEAM_REPOSITORY_STANDARD.md](TEAM_REPOSITORY_STANDARD.md).

The required folders and files should be created early in the project rather than at the end.

## Step 6 — Work Through GitHub

During delivery:

- create issues for meaningful tasks;
- assign owners;
- use branches for substantial work;
- make descriptive commits;
- use pull requests for major merges;
- document important decisions;
- maintain the contribution record.

Do not wait until Week 6 and upload everything in one commit.

## Step 7 — Complete FINAL_SUBMISSION.md

Create:

```text
submission/FINAL_SUBMISSION.md
```

It must contain:

### Submission details
- Project ID
- team name
- Team Lead
- team members
- submission date

### Repository
- repository URL
- default/final branch
- release/tag

### Deliverables
Links to every required deliverable.

### Dashboard
Link/file location and access instructions.

### Key findings
Concise summary of major findings.

### Recommendations
Concise management recommendations.

### Known limitations
Important analytical, data and implementation limitations.

### Contribution evidence
Link to `CONTRIBUTIONS.md`.

### Declaration
Confirmation that the work is the team's own, sources are acknowledged, and the simulated confidential client has not been represented as a real external Mettelo customer.

## Step 8 — Perform Final QA

Before submission verify:

- [ ] repository name follows the standard;
- [ ] GitHub user `OlaoluwajohnsonT` has been invited and access verified;
- [ ] README is complete;
- [ ] required structure exists;
- [ ] data-download instructions work;
- [ ] code is reproducible;
- [ ] dashboard link works;
- [ ] all required deliverables are present;
- [ ] CONTRIBUTIONS.md is complete;
- [ ] FINAL_SUBMISSION.md is complete;
- [ ] no secrets, passwords or API keys are committed;
- [ ] source dataset is attributed;
- [ ] all external links are accessible.

## Step 9 — Submit the Repository URL

The final submission is the URL of the team's GitHub repository.

Example:

```text
https://github.com/<owner>/MTL-DA-001-north-star-analytics
```

Mettelo will specify the central form or platform field where this URL should be submitted.

**Do not send project files by email.**

## Step 10 — Freeze the Reviewed Version

At the deadline, create a Git release or tag:

```text
v1.0-mettelo-submission
```

Mettelo will review the tagged version unless otherwise agreed.
