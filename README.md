# .github

David-Noble-at-work's own repository. GitHub serves the community health files and issue templates kept here to every
David-Noble-at-work repository that doesn't have its own. It also holds the account's issue model and its Triage
workflow template, and runs that workflow on its own issues.

| File | What it is |
| --- | --- |
| `model.yaml` | The account's issue model: its type labels, the labels of its repositories that carry the topic `issue-model`, and its projects, as `star github model pull` writes it; star reads it from here |
| `CONTRIBUTING.md` | The terms of a contribution: the sign-off and the AI disclosure on every pull request |
| `SECURITY.md` | How to report a vulnerability privately |
| `SUPPORT.md` | Where to ask a question or report a problem |
| `.github/ISSUE_TEMPLATE/` | The issue forms, one for each type label |
| `.github/pull_request_template.md` | The description every pull request starts from |
| `workflow-templates/triage.yml` | The Triage workflow template: a new issue goes to Triage: David-Noble-at-work, with its Area and Severity labels |
| `.github/workflows/triage.yml` | This repository's own Triage workflow, a copy of the template |
| `.github/workflows/quality-gate.yml` | This repository's own check: every YAML and JSON file parses |
