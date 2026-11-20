---
title: "6. Evidence that holds up"
description: "What auditors accept as proof, how they sample, and how to collect evidence once instead of scrambling at the end."
---

## What makes evidence good

An auditor needs to see that a control happened, when, on which system, and by whom. Good evidence is:

- **Dated.** The date is part of the record, not typed on later.
- **Attributable.** It shows who did or approved the thing.
- **From the system of record.** An export from the identity provider beats a hand-typed list of users.
- **Complete.** It covers the whole period and the whole population, including the instances that went badly.
- **Unedited.** A screenshot shows the URL or system name and the clock. Cropped ones raise questions.

> [!NOTE]
> **Weak and strong**
>
> Weak: "Quarterly access review done, see notes." Strong: an exported user list from each system, dated, with the reviewer's initials beside each kept or removed account, and the tickets for the removals.

## How auditors sample

In a Type II, the auditor doesn't check every event. They ask for the **population**, a complete list of every time the control should have run, then pick a **sample**.

- **Every-event controls** (access requests, pull requests, departures): the full list for the window, then a sample. The sample grows with the population, and a few dozen is common for frequent events.
- **Quarterly controls:** usually two or more instances, or all of them in a short window.
- **Yearly controls:** the one instance.

Two consequences follow. You must be able to produce a complete population, so log events somewhere instead of handling them in chat. And one missed instance in a small population is a big share of it, so a missing quarter shows up as soon as the auditor asks.

## Exceptions are survivable

An **exception** is a sample that failed. It appears in the report with your management response explaining what happened and what you changed. Readers weigh how serious it is and how you responded. One isolated exception reads very differently from a pattern in one area. A **qualified opinion** means a control failed badly enough that a criterion wasn't met. That's the result to avoid.

## Collect as you go

Don't collect evidence in the last two weeks. Set up collection once:

1. **Use tickets for every manual control.** One recurring ticket per control instance, assigned to the owner, closed with the evidence attached.
2. **Turn on the logs you'll need**, with retention longer than the observation window plus a few months.
3. **Export settings evidence once per window** for automated controls (branch protection, MFA enforcement, encryption), and again if they change.
4. **Track it in one place.** The [evidence tracker](../templates/evidence-tracker.csv) lists each control, each expected instance, where the proof lives, and its status.

The [evidence checklists](../evidence/index.md) show what auditors ask for in each area.

## Exercise: start the tracker

Copy the evidence tracker. For each control, fill in the expected instances for the next three months and where the evidence will live. Then collect one real piece of evidence for three controls today, and check each against the five qualities above.

## Check

1. What's a population, and why must it be complete?
2. Why does a missed quarterly control show up so easily?
3. What turns an exception into a qualified opinion?

## Sources

- [SOC suite of services](https://www.aicpa-cima.com/resources/landing/system-and-organization-controls-soc-suite-of-services), from the AICPA: what SOC 1, SOC 2, and the other SOC reports are, and who issues them.
- [2017 Trust Services Criteria, with revised points of focus (2022)](https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022), from the AICPA: the criteria SOC 2 reports measure against, cited here by ID.
