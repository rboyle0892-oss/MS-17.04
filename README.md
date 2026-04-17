# Microsoft Power Platform Vendor Management Repository

This repository is the **foundation workspace** for managing and improving a Microsoft Power Platform vendor management solution.

It is intentionally minimal so you can:
- add an unmanaged solution export,
- unpack and source-control its contents,
- review and clean up artifacts,
- and document architecture and process decisions.

## Repository structure

- `/solution/exports`  
  Place your **unmanaged Microsoft solution export ZIP** here.

- `/solution/src`  
  Use this folder for the **unpacked/source-controlled solution contents**.

- `/docs`  
  Working documentation for process, architecture, data model, and flows.

- `/analysis`  
  Analysis notes, repo reviews, and cleanup planning.

## Next step

1. Export your unmanaged Power Platform solution as a `.zip` file.
2. Put that file in: **`/solution/exports`**.
3. In a follow-up step, unpack into `/solution/src` and begin cleanup/review.

## Scope for this setup phase

This initial commit creates only structure and starter documentation.
No business logic or generated solution content is modified here.
