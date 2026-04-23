# AGENTS.md

## Purpose
Guidance for future Codex runs in this repository.

## Working rules
1. **Preserve original exports**
   - Treat files in `/solution/exports` as immutable source artifacts.
   - Do not modify, rename, or overwrite original export ZIP files.

2. **Prefer minimal, safe changes**
   - Keep edits narrowly scoped to the task.
   - Avoid broad refactors unless explicitly requested.

3. **Avoid unnecessary rewrites of generated Power Platform files**
   - Do not reformat or rewrite generated solution files just for style.
   - Change generated artifacts only when required for a clear objective.

4. **Separate structural cleanup from business-process redesign**
   - First: organize, normalize structure, and document findings.
   - Later (explicitly requested): redesign process logic, data behavior, or business rules.

5. **Document before major change**
   - Capture rationale in `/analysis` or `/docs` before substantial transformations.

6. **Keep tooling minimal**
   - Do not add new tooling unless there is a clear, stated benefit for this repository.

## Preferred workflow order
1. Import/export handling (`/solution/exports`)
2. Unpacked source baseline (`/solution/src`)
3. Structural review and cleanup plan (`/analysis`)
4. Documentation updates (`/docs`)
5. Controlled implementation changes (when requested)
