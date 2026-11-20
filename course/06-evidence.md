---
title: "6. Evidence that holds up"
description: "What auditors accept as proof, how they sample, and how to collect evidence once instead of scrambling at the end."
---

## What makes evidence good

An auditor needs to see that a control happened, when, on which system, and by whom. Good evidence is:

- **Dated,** with the date part of the record, not typed on later.
- **Attributable:** it shows who did or approved the thing.
- **From the system of record.** An identity provider export beats a hand-typed user list.
- **Complete:** the whole period and population, including instances that went badly.
- **Unedited.** A screenshot shows the URL or system name and the clock.

Weak: "Quarterly access review done, see notes." Strong: a dated user export from each system, with the reviewer's initials beside each kept or removed account, and the tickets for the removals.

## How auditors sample

In a Type II, the auditor asks for the **population**, a complete list of every time the control should have run, then picks a **sample**.

| Control runs | Auditor typically tests |
|---|---|
| Every event (access requests, pull requests, departures) | The full list for the window, then a sample that grows with the population. A few dozen is common. |
| Quarterly | Two or more instances, or all of them in a short window |
| Yearly | The one instance |

Log events somewhere other than chat, or you can't produce a complete population.

An **exception** is a sample that failed. It appears in the report with your management response explaining what happened and what you changed. One isolated exception reads very differently from a pattern in one area. A **qualified opinion** means a control failed badly enough that a criterion wasn't met. That's the result to avoid.

## Collect as you go

1. **Use a recurring ticket for every manual control,** assigned to the owner and closed with the evidence attached.
2. **Turn on the logs you'll need,** retained longer than the window plus a few months.
3. **Export settings evidence once per window** for automated controls (branch protection, MFA enforcement, encryption), and again if they change.
4. **Track it in one place.** The [evidence tracker](../templates/evidence-tracker.csv) lists each control, each expected instance, where the proof lives, and its status.

The [evidence checklists](../evidence/index.md) show what auditors ask for in each area.

## Exercise

Copy the evidence tracker and fill in each control's expected instances for the next three months and where the evidence will live. Then collect one real piece of evidence for three controls today and check each against the five qualities above.

## Sources

- [SOC suite of services](https://www.aicpa-cima.com/resources/landing/system-and-organization-controls-soc-suite-of-services), AICPA.
- [2017 Trust Services Criteria, with revised points of focus (2022)](https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022), AICPA.
