---
title: "Evidence: continuity and backups"
description: "Proof that backups run and are kept apart, restores are tested, and a continuity plan is current."
---

Controls: BCP-01 to BCP-03.

## Auditor asks for

- [ ] Backup configuration for each in-scope data store: frequency, retention, encryption, and where copies are kept.
- [ ] Backup job history or failure alerts across the window.
- [ ] The yearly restore test: real data restored into a separate environment, from when, how long it took against the recovery time objective.
- [ ] The business continuity plan, with recovery targets and a review date.

## Common exceptions

- Backups that were never restored.
- Backups in the same account as production, with the same administrators.
- A continuity plan that names someone who left.

## Sources

- [2017 Trust Services Criteria, with revised points of focus (2022)](https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022), AICPA.
- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001), ISO. The standard is paid.
