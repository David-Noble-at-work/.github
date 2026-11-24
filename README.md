# .github

David-Noble-at-work's own repository. GitHub serves the community health files and issue templates kept here to every
David-Noble-at-work repository that doesn't have its own. It also holds the account's issue model and its workflow
templates, Triage and the daily credentials check, and runs both on itself.

| File | What it is |
| --- | --- |
| `model.yaml` | The account's issue model: its type labels, the labels of its repositories that carry the topic `issue-model`, and its projects, as `star github model pull` writes it; star reads it from here |
| `CONTRIBUTING.md` | The terms of a contribution: the sign-off and the AI disclosure on every pull request |
| `SECURITY.md` | How to report a vulnerability privately |
| `SUPPORT.md` | Where to ask a question or report a problem |
| `.github/ISSUE_TEMPLATE/` | The issue forms, one for each type label |
| `.github/pull_request_template.md` | The description every pull request starts from |
| `workflow-templates/triage.yml` | The Triage workflow template: a new issue goes to Triage: David-Noble-at-work, with its Area and Severity labels |
| `workflow-templates/credentials-check.yml`, `credentials-check.sh` and `credentials-check.json` | The daily credentials check: its workflow, script and permissions file. The New workflow page doesn't offer it, since the workflow alone can't run: a repository takes all three by hand, the workflow in `.github/workflows/` and the script and permissions file in `.github/credentials-check/`; the secret and variables it reads, and how to run it once to check it, are in [the credentials guide, § 7](https://github.com/NobleFactor/noblefactor-engprod/blob/develop/docs/reference/issue-tracking-credentials.md#checking). Their source is noblefactor-engprod's `workflow-templates/` (NobleFactor/noblefactor-engprod#613) |
| `.github/workflows/triage.yml`, `credentials-check.yml` and `.github/credentials-check/` | This repository's own Triage and daily credentials check, copies of the templates |
| `.github/workflows/quality-gate.yml` | This repository's own check: every YAML and JSON file parses |
