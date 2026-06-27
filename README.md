# rulespec-us-tx

This repository is archived. Its canonical content now lives in
[`TheAxiomFoundation/rulespec-us`](https://github.com/TheAxiomFoundation/rulespec-us)
under `us-tx/`; keep all future RuleSpec work there.

Texas RuleSpec encodings and source registry metadata.

## Contents

- `statutes/`: Texas statute RuleSpec YAML, with tests beside each encoding as `.test.yaml`.
- `regulations/`: Texas regulation RuleSpec YAML, with tests beside each encoding as `.test.yaml`.
- `policies/`: Texas policy RuleSpec YAML, with tests beside each encoding as `.test.yaml`.
- `sources/`: source registry or manifest metadata when needed.
- `.github/workflows/repository-checks.yml`: wrapper around the shared RuleSpec validation workflow.

## Conventions

Use RuleSpec YAML for encoded rules. Do not add singular rule roots, separate
parameter/test fixture files, or generated formula artifacts.

In the canonical monorepo, Texas-administered materials live under `us-tx/`; shared federal materials live at the country root.
