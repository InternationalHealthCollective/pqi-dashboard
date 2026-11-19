# PQI Dashboard

> **Fill in:** one or two sentences on what this project does and who uses it.

| | |
|---|---|
| Owning team | _fill in_ |
| Leads | _fill in_ |
| Status | Active |
| Stack | _fill in_ |
| Where it runs | _fill in_ |
| Non-code files | IHC Google Drive (link: _fill in_) |

> **This repository is public.** Anyone on the internet can read everything committed here, including old commits.

## Layout

```
pqi-dashboard/
├── README.md        this file: what it is, how to run and deploy
├── HANDOFF.md       current status and next steps
├── src/             the code
├── docs/            design notes, protocols, sign-off records
├── examples/        synthetic sample data only
└── .github/
    └── pull_request_template.md
```

## How to run

_fill in_: setup steps, where the code is deployed, and how to deploy a new version.

## Rules

- **No real patient, applicant or staff data**, in code, examples, tests, screenshots or logs. Use invented records.
- **No secrets** (API keys, passwords, service-account files, sheet IDs that grant access). Keep them in a
  git-ignored `.env` or in script properties, and share them through the team's password manager or Drive.
- Work on a branch and open a pull request into `main`; someone else reviews before merging.
- Changes to clinical logic (triage rules, lab thresholds, patient-facing wording) need a clinical lead's sign-off,
  recorded in `docs/`.
- Update `HANDOFF.md` when you stop working on this or hand over your role.

New to Git? Start with the [Onboarding](https://github.com/InternationalHealthCollective/Onboarding) repository.
