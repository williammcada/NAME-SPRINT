# Migration Baseline — NameSprint

**Recorded:** 18 September 2026  
**Repository:** `williammcada/NAME-SPRINT`  
**Branch:** `main`  
**Source-preservation checkpoint:** `da7fccb1fa5e92449a682ba2689a01b890174233`  
**Record status:** Current source identity. This is not by itself a functional-test, release, or deployment claim.

## Canonical source identity

| Field | Value |
| --- | --- |
| Canonical source path | `NameSprint.html` |
| Git blob SHA | `a37fcdb8ecbf2c6c20870ded5f2262abf10d4007` |
| Version represented | Semantic app version not established; backup schema 3 is separate |
| Repository source checkpoint | `da7fccb1fa5e92449a682ba2689a01b890174233` |

The checkpoint above identifies the application/planning source immediately before this normalization record was committed. Later documentation-only commits do not change the preserved application bytes.

## Verification status

| Check | Result | Evidence / limitation |
| --- | --- | --- |
| Source exists in the default branch | Passed | Repository paths and Git object identities were read directly on 18 September 2026. |
| Byte-preservation comparison | Passed | Passed — the Git blob matched the preserved Library source during the 18 September 2026 audit. |
| Functional workflow | Not run | Source preservation does not establish that imports, gameplay, reports, storage or exports work. |
| Hosted/running application | Not run | Not verified; hosting would create a different browser-storage origin and requires separate migration checks. |

## Documentation authority

- [`PROJECT-BRIEF.md`](PROJECT-BRIEF.md) records purpose, scope, must-retain behavior and verification requirements.
- [`change-specs/INDEX.md`](change-specs/INDEX.md) identifies approved or directional change records.
- [`MIGRATION-NOTE.md`](MIGRATION-NOTE.md) is retained as historical migration context but its pre-upload source-status language is superseded by this baseline.
- This file controls current source identity when an older brief or note says the source was unknown or “TO ESTABLISH.”

## Next gate

Use the committed `NameSprint.html` as the baseline, preserve local-only privacy behavior, and assign an app version only through a future verified release.

Do not label a future commit a verified release until the exact candidate has passed the project brief’s required verification and that evidence is preserved.
