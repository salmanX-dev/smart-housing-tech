# Smart Housing - Initial Requirements

**Document status:** Initial draft for Assignment 1; revise as the group validates the application and agrees on scope.

## 1. Project and group

**Project title:** Smart Housing - Residential Architecture Planning Software

| Name | GitHub username |
|---|---|
| Muhammad Sanan | `sanan14356` |
| Zain Ali | `Zainalii22` |
| Salman Khan | `salmanX-dev` |

## 2. Problem statement

Planning a house requires arranging rooms within a plot while considering the building rules that apply to that location. It can be difficult for homeowners and learners to explore layouts and spot possible rule conflicts. Smart Housing is intended to support early residential layout planning and provide rule-based feedback for selected profiles.

## 3. Objectives

- Allow a user to define a plot and prepare a residential floor plan.
- Help users arrange and edit rooms and plan elements.
- Provide rule profiles intended for CDA, PDA, LDA, DHA, and custom values, subject to implementation and verification.
- Show possible violations or warnings so users can review a plan.
- Allow users to preserve and share their work if the adopted implementation supports those operations.

## 4. Intended users

- Homeowners exploring possible house layouts.
- Architecture and engineering students learning about residential planning.
- Design professionals preparing or discussing early concepts.

## 5. Initial functional requirements

These are proposed initial requirements. The group must compare them with the adopted code and its agreed scope before treating them as implemented.

| ID | Requirement | Priority |
|---|---|---|
| FR-01 | The application shall let a user enter the plot dimensions and relevant orientation details. | Must |
| FR-02 | The application shall let a user create and edit a residential floor plan by adding and arranging rooms and other supported plan elements. | Must |
| FR-03 | The application shall let a user select a supported building-rule profile, or enter custom rule values when that feature is available. | Must |
| FR-04 | The application shall check supported plan properties against the selected rule values and show issues or warnings to the user. | Must |
| FR-05 | The application should let a user save a plan and reopen it later. | Should |
| FR-06 | The application should let a user export or print a plan in supported formats. | Should |
| FR-07 | The application may provide starter layouts, suggestions, or automatic assistance where supported by the adopted code. | Could |

## 6. Initial non-functional requirements

| ID | Requirement | Priority |
|---|---|---|
| NFR-01 | The interface should make common planning actions understandable to a first-time user. | Should |
| NFR-02 | The application should preserve a user's work through its supported save mechanism and explain where data is stored. | Must |
| NFR-03 | The application should clearly identify the selected rule profile and communicate warnings without implying official approval. | Must |
| NFR-04 | The application should run in the browsers and environments confirmed by the group during implementation. | Should |
| NFR-05 | Changes should be maintained in a shared Git repository with meaningful, attributable commits. | Must |

## 7. Initial product backlog

See [`backlog.md`](backlog.md) for the prioritized backlog and acceptance notes.

## 8. Assumptions

- A user can provide or obtain the plot measurements needed to create a plan.
- The group will identify the geographic jurisdiction or society for each rule profile.
- The group will check rule values against current, authoritative sources before presenting them as verified.
- The supplied `Architecture-Software.zip` is a candidate starting point, not yet confirmed as the final Smart Housing codebase.

## 9. Constraints

- The assignment requires a public shared GitHub repository, meaningful contributions from each member's own GitHub account, an included requirements document, a README, and an evolving task list.
- The initial submission is a lightweight requirements document; a formal SRS is not required.
- Team members should document only features and rule coverage that they have confirmed in the adopted code.
- Available time, tools, and the accuracy and completeness of source data may limit the first release.

## 10. Known limitations and risks

- The supplied archive is branded GharPlan, so the group must decide whether to adopt and rebrand it as Smart Housing.
- In the inspected archive, the rule data contains a PDA Peshawar profile, approximate LDA and CDA profiles, and custom rules. A DHA profile was not found. These are observations about the supplied archive and may change as the group reviews or extends it.
- The supplied archive labels some rule data approximate. Current local regulations and society-specific rules need verification; software checks cannot guarantee approval.
- Import, export, storage, accessibility, browser compatibility, and security behavior require validation against the version the group chooses to maintain.
- Requirements and backlog priorities are initial and should evolve through team discussion.

