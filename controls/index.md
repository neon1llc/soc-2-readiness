---
title: How to read the controls map
description: "What each column in the controls map means, how the SOC 2 and ISO 27001 references work, and how to make the map your own."
---

The [controls map](controls-map.md) is generated from [controls.csv](controls.csv). Copy the CSV into a spreadsheet to make your own.

| Column | Meaning |
|---|---|
| **ID** | A short code by area, such as ACC-03. Keep IDs when you rewrite a control so your tracker and risk register still line up. |
| **Control** | What the company does, written so it can be tested. |
| **Owner** | The role that makes sure it happens. Replace with names in your copy. |
| **How often** | Continuous (enforced by a system), on every event, or on a schedule. |
| **Evidence** | What an auditor will ask to see. |
| **SOC 2** | Trust Services Criteria IDs the control helps meet. CC is the common criteria (Security), A1 is Availability, and C1 is Confidentiality. |
| **ISO 27001** | ISO/IEC 27001:2022 Annex A control numbers (such as 8.32) and management system clauses (such as Clause 9.3) the control relates to. |

A reference means the control is a reasonable way to help meet that criterion or Annex A control, not that it satisfies it alone. Auditors judge sufficiency for your situation. Read the AICPA criteria and ISO/IEC 27001 themselves before you rely on a mapping.

To make the map yours, work through [module 4](../course/04-controls.md). If you edit the CSV here, run `node tools/build-map.mjs` to rebuild the map and coverage table. The check workflow fails if a criterion is left uncovered.

Processing Integrity (PI1) and Privacy (P1 to P8) controls aren't here, because most first reports leave them out. To add them, add rows and extend the criteria list in `tools/build-map.mjs`.

## Sources

- [2017 Trust Services Criteria, with revised points of focus (2022)](https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022), AICPA.
- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001), ISO. The standard is paid.
- [Mapping: 2017 Trust Services Criteria to ISO 27001](https://www.aicpa-cima.com/resources/download/mapping-2017-trust-services-criteria-to-iso-27001), AICPA.
