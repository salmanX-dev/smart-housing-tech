# Building-rule profile evidence log

**Project:** Smart Housing  
**Research contributor:** Zain Ali (`Zainalii22`)  
**Assignment task:** B-04 — research CDA, PDA, LDA, DHA, and custom rule profiles  
**Date checked:** 20 October 2026  
**Status:** Preliminary research; not a certification of legal compliance or working application code.

## How I classified the findings

- **Verified document provision:** A precise requirement was read from a document published by the relevant authority. This does **not** verify the application's values or guarantee no later amendment.
- **Approximate:** A candidate preset is described by the existing repository as approximate; its numerical values have not been checked.
- **Not found:** A feature was not located in the particular source reviewed; this does not prove no implementation exists anywhere.
- **Still needs research:** The available evidence is not enough to confirm a regulation's applicability or the application's implementation.

## Evidence table

| Profile | Issuing authority and document/page | Official source URL | Checked | Evidence and status | Gaps / next action |
|---|---|---|---|---|---|
| PDA | Peshawar Development Authority; *PDA (Building Control) Regulations, 2024*, Schedule-1, Gazette printed p. 973, PDF p. 21 | https://www.pda.kp.gov.pk/uploads/downloads/pdf-attchment-eb8ee58e1da100cb9601e30fce2aaed4.pdf | 2026-10-20 | **Verified document provision:** in **approved schemes/societies**, plots **above 7 to 10 marla**: minimum front 10 ft, back 10 ft, one side 5 ft; ground coverage 65%; FAR 1:1.25. Application implementation: **still needs research**. | Confirm the proposed plot is in this specific category and that no current amendment or scheme-specific rule overrides it. Compare the values with candidate code before marking any preset verified. |
| CDA | Capital Development Authority; official *By-Laws & Regulations* index | https://www.cda.gov.pk/lawsAndRegulations | 2026-10-20 | Official document index **found**, but numerical CDA requirements are **still needing research**. Existing repository calls its candidate CDA preset **approximate**. | Select the applicable residential-sector regulation and current amendments for the exact Islamabad location and plot category. Then inspect the candidate profile. |
| LDA | Lahore Development Authority; *LDA Building and Zoning Regulations 2019 (with amendments approved till 28-01-2020)* | https://lda.gop.pk/website/images/Amended_Building_Regulations_2019_with_amendment_approved_till_28_01_2020.pdf | 2026-10-20 | Official regulation PDF **found**; numerical LDA values **still needing research**. Existing repository calls its candidate LDA preset **approximate**. | The PDF's stated amendment cutoff is Jan 2020; check any newer effective rules, location, and applicable plot class. Then compare against code. |
| DHA | Defence Housing Authority **Lahore**; official *Construction & Development Regulations* PDF (URL dated April 2026) | https://dhalahore.org/wp-content/uploads/2026/04/20-Apr-2026-Byelaws-final.pdf | 2026-10-20 | Official DHA Lahore PDF **found**, but project DHA jurisdiction and applicable numeric values **still need research**. Existing README says DHA profile **not found** in its earlier candidate-archive review. | Confirm whether team means DHA Lahore, Islamabad/Rawalpindi, Peshawar, etc.; these should not be treated as interchangeable. Clarify version/amendments and inspect candidate code. |
| Custom | No issuing authority; user-provided settings defined by project | Not applicable | 2026-10-20 | A proposed project feature, **not an official regulation**; implementation **still needs research**. | Inspect the UI fields, defaults, validation, persistence and actual checks after the code is supplied. |

## PDA example I can explain in a viva

For a **PDA-approved residential scheme/society** plot strictly **above 7 marla and up to 10 marla**, Schedule-1 (p. 973) prints 65% ground plot coverage. For a simple *hypothetical* 2,000 sq ft plot in that exact category, 65% would correspond to 1,300 sq ft of ground coverage (2,000 × 0.65), **if** the plot size/unit and all applicability conditions are confirmed. This is arithmetic to understand the rule, not a determination that a real plot is compliant.

A rule checker should not apply this 65% to every PDA plot: the Gazette has **different rows** for different plot sizes and **Schedule-2** for residential houses outside approved schemes/societies. Final layout approval belongs to the authority.

## Candidate code audit — not yet completed

As checked on 20 October 2026, `salmanX-dev/smart-housing-tech` contains the four project Markdown files but **no committed GharPlan application source**. The candidate `Architecture-Software.zip` has not been provided in the current review. Therefore these earlier README statements are only leads, not my independent code findings:

| Profile | Prior README statement about candidate archive | My direct code verification | Current status |
|---|---|---|---|
| PDA | PDA preset described | No candidate code available | Still needs research |
| CDA | Approximate CDA preset described | No candidate code available | Approximate / still needs research |
| LDA | Approximate LDA preset described | No candidate code available | Approximate / still needs research |
| DHA | No DHA preset found in earlier review | No candidate code available | Not found in earlier review only |
| Custom | Custom values described | No candidate code available | Still needs research |

## How the team can finish B-04

1. Obtain the exact candidate ZIP and agree whether to adopt it in Smart Housing.
2. Locate the authority profile definitions and actual rule-checking functions. Record file path and line number for each observation.
3. For each numeric rule, compare the code value against an official provision applicable to a named location, plot category, and effective amendment date.
4. Test one case that passes and one that produces a warning, and record the results without treating the software output as official approval.
5. Ask the team to review the evidence and then update B-04 from **In progress** to **Completed** only if the acceptance notes have been met.

**Source limitation:** An official-source URL proves document availability and, where noted above, one carefully scoped PDA provision; it does not alone establish that all rules are up-to-date or that the software is implemented correctly.
