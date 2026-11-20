---
title: "Evidence: access"
description: "Proof that access is approved, reviewed, removed on time, protected with strong sign-in, and limited for administrators."
---

Controls: ACC-01 to ACC-06.

## What the auditor asks for

- [ ] In-scope systems, and who owns each.
- [ ] Access request tickets for the window (the population), and for a sample: requester, approver, date approved, date granted.
- [ ] Everyone who left during the window, with last day and the time each account was disabled in every in-scope system.
- [ ] Each quarter's access review: dated user export, reviewer's marks, removal tickets, and sign-off.
- [ ] Identity provider settings showing single sign-on and two-step sign-in enforced, and a report of who's enrolled.
- [ ] Administrators and production access holders, and evidence they're reviewed.
- [ ] Secrets and service account inventory, with owners and last rotation dates.

## What good looks like

Departures matched to disable times in one table, every gap under a business day. Access reviews that show removals, because a review that never removes anything looks like a rubber stamp.

## Common exceptions

- A departed person's account still active in a tool outside single sign-on.
- A quarterly review skipped or late, or one system left out.
- Two-step sign-in enforced for staff but not for a break-glass or shared admin account.
- An engineer granting themselves access with no approval.

## Sources

- [2017 Trust Services Criteria, with revised points of focus (2022)](https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022), from the AICPA: the criteria SOC 2 reports measure against.
- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001), from ISO: the management system standard and its Annex A controls. The standard is paid.
