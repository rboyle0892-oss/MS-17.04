# Microsoft Power Platform Vendor Management Repository

This repository is the working foundation for cleanup, review, redesign planning, and documentation of a Microsoft Power Platform vendor management solution.

## Repository structure

- `/solution/exports`  
  Place your **unmanaged Microsoft solution export ZIP** here. Keep the original export unchanged for traceability.

- `/solution/src`  
  Destination for **unpacked/source-controlled solution contents** used for review and cleanup.

- `/docs`  
  Process, architecture, data model, and flow documentation.

- `/analysis`  
  Repository and solution analysis notes, findings, and review plans.

## Intake workflow

1. Add the unmanaged solution `.zip` into `solution/exports`.
2. Preserve the original ZIP (do not edit/overwrite it).
3. Unpack into `solution/src` for source control and review.
4. Update docs in `/docs` and findings in `/analysis`.

## Current status

- Repo scaffold is in place.
- In this environment, no export ZIP is currently detected in `solution/exports`, so unpack/content inventory has not yet occurred.
