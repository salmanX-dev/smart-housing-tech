# Smart Housing

Smart Housing is an architecture planning application intended to help users create residential house plans using selected building-rule profiles for CDA, PDA, LDA, DHA, and user-defined custom rules.

> **Project status:** Assignment 1 planning and repository setup. The group still needs to confirm the application source, verify which rule profiles are implemented, and agree on the development scope. The supplied archive is branded **GharPlan**. Its code includes a PDA profile, approximate LDA and CDA profiles, and custom rules; a DHA profile was not found in the inspected rule data. Do not describe a rule profile as implemented or officially verified until the group checks the code and current authority rules.

## Problem

People planning a home need to consider plot dimensions, room arrangements, and local building rules. Smart Housing aims to make early layout planning and rule checking easier to understand. Its output is for planning support and must not be treated as official approval or a substitute for review by a qualified professional.

## Objectives

- Let users enter plot details and plan residential layouts.
- Provide rule profiles for the target authorities and allow custom rule values, as the implementation supports them.
- Help users identify possible rule conflicts while editing a plan.
- Save, reopen, and export their work, if supported by the adopted implementation.

## Intended users

- Homeowners and people exploring residential layouts.
- Architecture and engineering students.
- Architects, draftspeople, or builders preparing an early concept for discussion.

## Group members

| Name | GitHub username | Initial responsibility |
|---|---|---|
| Muhammad Sanan | To be added | Suggested: repository setup and source review |
| Zain Ali | To be added | Suggested: rule-profile research and verification |
| Salman Khan | To be added | Suggested: requirements, backlog, and documentation coordination |

Each member should use their own GitHub account and make traceable contributions to the shared repository.
These are draft role suggestions; agree on them as a group and update this table.

## Repository contents

- `README.md` — project overview and current status.
- `docs/requirements.md` — initial requirements, assumptions, constraints, and limitations.
- `docs/backlog.md` — prioritized initial work list.
- `contribution.md` — team collaboration and contribution guidance.
- `model/` — application source, once the group confirms and adopts the supplied code.

## Getting started

The supplied archive's application is under `model/` and its README says to open `model/index.html` in Chrome or Edge. Confirm this remains valid after adopting the source and renaming/rebranding it as Smart Housing. See `model/README.md` for its existing usage details.

## Current project status

**In progress:** agree the initial project scope, create the shared public GitHub repository, add all members as collaborators, review the supplied application source, and commit this assignment documentation. Update this section as the team makes progress.

## Versioning

Use Git history and tags for project versions. Suggested first planning tag: `v0.1.0`. Do not create duplicate file copies to represent versions.

## Important limitations

- Building regulations can change and may vary by location or housing society. Confirm current requirements with the relevant authority.
- Rule checks are planning aids, not a guarantee of legal compliance or approval.
- The supplied code describes its LDA and CDA presets as approximate. The inspected rule data did not contain a DHA preset.
- Supported browsers, import/export behavior, and data storage should be confirmed against the version the group adopts.

