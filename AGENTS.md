<!-- FLEET-CANON-POINTER:begin -->
> **Fleet Canon (`canon_version: 1`):** This repo follows the fleet's operating contract, which is kept in the private fleet vault. Agents with vault access load it from there; it is not reproduced in this public repo.
<!-- FLEET-CANON-POINTER:end -->

## Change Verification

Before changing code, trace direct callers and imports in source and assess affected behavior. Surface material risks before proceeding. Before committing, inspect the diff for unintended changes and run the relevant normal tests and checks.

GitNexus is optional, only when explicitly requested; it is not an editing or commit prerequisite. Do not run it or reindex automatically.