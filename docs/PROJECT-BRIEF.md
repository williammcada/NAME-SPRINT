# Project Brief — NameSprint

**Brief status:** Migration baseline / requires source verification where noted  
**Brief version:** 0.1  
**Last updated:** 18 September 2026  
**Owner:** William McAda  
**Product credit:** A WILLIAM MCADA PRODUCT  
**Handbook repository:** `williammcada/mcada-project-handbook`  
**Handbook baseline:** `6557a45aaa6d29d7d1abde808e6d0ac248b08820 (AI-START-HERE.md); UNIVERSAL-RULES.md @ aed6fe311aa2e88983f862a30a2d8f05d2ffc04d`  
**Repository:** `williammcada/NameSprint`  
**Canonical source status:** A standalone offline HTML build exists; exact filename/version is TO ESTABLISH from the latest local known-good file before substantive revision.  
**Current project state:** Working standalone local application with local roster/photo import, multiple practice modes, mastery tracking, backup/restore, and network blocking.

## 1. Purpose and audience

NameSprint is an offline teacher training game for learning students' names quickly from class rosters and photos.

**Primary audience / operator:** Teacher learning student names before or during the beginning of a course.

## 2. Standards selection

**Universal baseline:** U-01 through U-08 where applicable.

**Conditional modules:** S-04 Distribution/Deployment

Apply only the selected modules and project-local requirements. Do not import restrictions from unrelated projects.

## 3. Project-specific requirements

- Must run locally on phone, tablet, and computer as an HTML application.
- Student names/photos/data must not be uploaded.
- Imports of supported DOCX/PDF/CSV files must be processed locally.
- Maintain roster verification before practice.
- Support named classes and class deletion.
- Preserve Face → Name and Name → Face modes with 4/6/8-choice difficulty settings where implemented.
- Preserve Type Name mode.
- Keep class-specific mastery at the established 90% threshold unless explicitly revised.
- Use adaptive review and local persistence.
- Support local backup import/export.
- Preserve embedded pixel-art hare mascot and block unintended network access.

## 4. Preserve from the current accepted project

- Offline/local-only student-data handling.
- Local roster/photo import and verification.
- Multiple class management.
- Face→Name, Name→Face, and Type Name practice.
- Adaptive review and 90% class-specific mastery.
- Local persistence and backup/restore.
- Network blocking.

## 5. Relationship to other projects

- Standalone teacher utility/game; student privacy rules are local and unusually strict because real roster/photo data may be imported.
- Do not integrate learner accounts, analytics, or cloud storage without a separate explicit privacy/design decision.

A conceptual relationship is not proof of an implemented integration. Do not invent a shared API, data schema, identity layer, or deployment dependency without an explicit integration task.

## 6. Source and version discipline

The exact current source artifact or repository commit must be identified before a substantive build. If the field above says the source is not yet established, first locate the latest known-good local file/ZIP or existing repository state and record its exact identity here.

For substantial revisions use:

**DESIGN → CHANGE SPEC → IMPLEMENT → CHECKPOINT → VERIFY → VERIFIED CHECKPOINT → RELEASE → DEPLOY (when applicable)**

A packaging/export/deployment failure must not force reconstruction of an already verified build.

## 7. Definition of done

| # | Requirement / check | Result | Evidence / limitation |
| ---: | --- | --- | --- |
| 1 | Supported files import locally without uploading roster/photo data. | Not run | |
| 2 | Network blocking prevents unintended external data transmission. | Not run | |
| 3 | Roster verification and class deletion work correctly. | Not run | |
| 4 | All practice modes score correctly. | Not run | |
| 5 | Mastery/adaptive-review behavior matches the documented 90% rule. | Not run | |
| 6 | Backup/restore reproduces class data locally. | Not run | |
| 7 | Phone/tablet/computer local HTML operation works on claimed targets. | Not run | |

Allowed results: **Passed / Failed / Not run / Not applicable**. A "Passed" result requires an actual check against the identified candidate.

## 8. Known issues and migration notes

The privacy boundary is a must-retain feature: migration to GitHub is for source/version control, not permission to upload actual student rosters or photos into the repository.

## 9. Handoff files

A substantive AI implementation task should retrieve or receive:

1. `AI-START-HERE.md`;
2. `UNIVERSAL-RULES.md`;
3. the relevant sections of `CONDITIONAL-STANDARDS.md`;
4. this project brief;
5. the exact current source artifact/commit;
6. the approved version-specific change specification;
7. applicable assets and deployment configuration.

Do not reconstruct the current implementation from a historical chat summary when the actual source should be available.

## 10. Ownership

**William McAda**  
**A WILLIAM MCADA PRODUCT**
