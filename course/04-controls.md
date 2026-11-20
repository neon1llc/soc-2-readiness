---
title: "4. Write controls you can keep"
description: "Turn the starter controls map into your own list: testable statements with an owner, a frequency, and the proof each leaves behind."
---

## What a control is

A control is something the company does, on a schedule or on every event, that leaves a record. A good one reads:

> System owners review who has access to each production system every quarter, remove access that's no longer needed, and record the review in a signed ticket.

That has an **owner,** an **activity,** a **frequency,** and **evidence.** "Access is reviewed regularly" has none.

- **Automated** controls are enforced by a system, such as branch protection requiring a reviewer. The auditor tests the design once, then checks settings and a sample. They rarely fail unless someone changes the setting.
- **Manual** controls depend on a person remembering, such as quarterly access reviews. They fail far more often, usually because the owner was away or left. Keep them few, put them on a shared calendar, and give each a backup owner.

## Cutting the map down

The [controls map](../controls/controls-map.md) has 44 starter controls. Expect to keep most, in your words. For each row, ask:

1. **Do we do this today?** If yes, rewrite it to match what you do, not what the template says.
2. **If not, should we?** Start it if a high risk in your register depends on it. Otherwise, cut it if no criterion goes uncovered without it.
3. **Can we keep doing it for the whole window?** If not, simplify or automate it.
4. **Does it leave proof without extra work?** Prefer a system log or a ticket you'd create anyway.

Then rebuild the coverage table (`node tools/build-map.mjs` if you're editing the CSV here) and check that every in-scope criterion still has a control. Every control you write becomes a test. A control that says "monthly" and runs quarterly is an exception, even if quarterly is secure.

## Exercise

Copy [controls.csv](../controls/controls.csv) into a spreadsheet and mark each row *keep*, *rewrite*, *start*, or *cut*. Rewrite the kept rows with your real owners and frequencies. Add a target date to your [90-day plan](../plan/90-day-plan.md) for each *start*.

## Sources

- [2017 Trust Services Criteria, with revised points of focus (2022)](https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022), AICPA.
- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001), ISO. The standard is paid.
