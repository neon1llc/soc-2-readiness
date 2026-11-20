---
title: "1. Decide why, and which report"
description: "Why you want SOC 2, whether it's the right answer yet, and how to choose between a Type I and a Type II report."
---

## Why the reason matters

SOC 2 takes sustained time from at least one person, plus an audit firm's fee. Fees vary by firm, scope, and report type, so get quotes first. Without a clear reason, scope creeps, nobody owns the work, and it stalls in a busy quarter.

The common reasons:

1. **A specific customer asked.** A deal is waiting. This sets your date and often your scope, so ask what they need covered.
2. **Your market expects it.** Every prospect sends a security questionnaire, and a report answers most of it at once.
3. **Investors or acquirers asked** during diligence.
4. **You want the discipline.** It rarely survives a busy quarter alone.

## When SOC 2 isn't the answer yet

A lighter step can close the deal for now:

- **A completed security questionnaire** (the customer's, or a standard one such as the CAIQ or SIG Lite) plus a short security overview page.
- **A letter describing your readiness work** and the date you expect the report.
- **ISO 27001** instead, if most of your customers are outside the United States. The [controls map](../controls/controls-map.md) shows how heavily the controls overlap.
- **Nothing formal**, if the customer only needs to know you use well-run cloud providers.

## Getting help

- **A compliance platform** (Vanta, Drata, and Secureframe are examples, not endorsements) collects evidence from your cloud, identity, and ticketing tools. It suits a team that already knows its controls. It doesn't set your scope or run your reviews, and it costs a subscription.
- **Your auditor's readiness assessment** shows whether the design looks right to the firm that may issue the report. Use it before a Type II window.
- **A consultant or virtual CISO** helps if nobody on the team has done this before.

This course replaces none of these. The AICPA guidance under Sources is the authority on what the report covers.

## Type I or Type II

A **Type I** report says your controls were designed well on one date, and it takes weeks after readiness. A **Type II** report says they also *worked* over a period, usually three to twelve months, called the observation window. It takes the window plus a few weeks, and it's what most customers ask for.

A common path is a Type I, then a Type II with a three-month window, then twelve-month windows. If your customer accepts only a Type II, start the window as soon as your controls run and skip the Type I.

> [!TIP]
> **Ask the customer**
>
> "Which report type and which criteria do you need, and by when?" Most security teams will tell you, and the answer can save months.

## Exercise: write your reason

On one page, answer:

1. Who asked, and what exactly did they ask for?
2. What happens if you don't have a report by then?
3. Type I first, or straight to Type II? Why?
4. The date you want the report in hand, and the date the window would have to start to make it.
5. Who owns the work, and what will they stop doing to make time?

Get leadership's yes on the page. That is your first evidence for control [GOV-01](../controls/controls-map.md#governance).

## Sources

- [SOC suite of services](https://www.aicpa-cima.com/resources/landing/system-and-organization-controls-soc-suite-of-services), from the AICPA: what the SOC reports are and who issues them.
- [Mapping: 2017 Trust Services Criteria to ISO 27001](https://www.aicpa-cima.com/resources/download/mapping-2017-trust-services-criteria-to-iso-27001), from the AICPA: the official crosswalk to check the ISO column.
- [SOC 2 readiness track](https://github.com/neon1llc/ready-secure-go/tree/main/content/tracks/soc2), in Ready, Secure, Go: the plain-language introduction this course builds on.
