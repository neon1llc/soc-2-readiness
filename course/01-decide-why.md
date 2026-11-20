---
title: "1. Decide why, and which report"
description: "Why you want SOC 2, whether it's the right answer yet, and how to choose between a Type I and a Type II report."
---

## Why the reason matters

SOC 2 takes sustained time from at least one person, plus an audit firm's fee. Fees vary widely by firm, scope, and report type, so get quotes first. Without a clear reason, scope creeps, nobody owns the work, and it stalls in a busy quarter.

The common reasons:

1. **A specific customer asked.** A deal is waiting on the report. This sets your date and often your scope, because you can ask the customer what they need covered.
2. **Your market expects it.** Every prospect in your segment sends a security questionnaire, and a report answers most of it at once.
3. **Investors or acquirers asked** during diligence.
4. **You want the discipline.** Writing things down and proving them makes a team better. It rarely survives a busy quarter on its own.

## When SOC 2 isn't the answer yet

A lighter step can close the deal for now:

- **A completed security questionnaire** (the customer's, or a standard one such as the CAIQ or SIG Lite) plus a short security overview page.
- **A letter describing your readiness work** and the date you expect the report.
- **ISO 27001** instead, if most of your customers are outside the United States. The controls overlap heavily, as the [controls map](../controls/controls-map.md) shows.
- **Nothing formal** if the customer only needs to know you use well-run cloud providers. Their SOC reports cover the data center, and yours would cover what you do on top.

## Doing it with help

Pick the help that fits the gap:

- **A compliance platform** (Vanta, Drata, and Secureframe are examples, not endorsements) connects to your cloud, identity, and ticketing tools and collects evidence automatically. It suits a team that already knows its controls and loses time gathering proof. It doesn't set your scope or run your reviews, and it adds a subscription cost.
- **Your auditor's readiness assessment** tells you whether the design looks right to the firm that may issue the report. Use it before you start a Type II window.
- **A consultant or virtual CISO** helps if nobody on the team has done this before.
- **The AICPA's own guidance**, linked under Sources, is the authority on what the report covers. This course prepares you and replaces none of these.

## Type I or Type II

A **Type I** report says your controls were designed well on one date. A **Type II** report says they also *worked* over a period, usually three to twelve months, called the observation window.

| | Type I | Type II |
|---|---|---|
| What it proves | Design, on one day | Design and operation, over a window |
| Typical time to report after readiness | Weeks | The window, plus a few weeks |
| What customers think of it | A good start | What most of them ask for |

A common path is a Type I first, then a Type II with a three-month window, then twelve-month windows. If your customer accepts only a Type II, start the observation window as soon as your controls run, and skip the Type I.

> [!TIP]
> **Ask the customer**
>
> "Which report type and which criteria do you need, and by when?" Most security teams will tell you, and the answer can save months.

## Exercise: write your reason

On one page, answer:

1. Who asked, and what exactly did they ask for?
2. What happens if you don't have a report by then?
3. Type I first, or straight to Type II? Why?
4. The date you want the report in hand, and the date the observation window would have to start to make it.
5. Who owns the work, and what they will stop doing to make time.

Get leadership's yes on the page. That is your first evidence for control [GOV-01](../controls/controls-map.md#governance).

## Check

1. What's the difference between a Type I and a Type II report?
2. Name two cases where something lighter than SOC 2 could close a deal.
3. Why does the reason you write down affect scope?

## Sources

- [SOC suite of services](https://www.aicpa-cima.com/resources/landing/system-and-organization-controls-soc-suite-of-services), from the AICPA: what SOC 1, SOC 2, and the other SOC reports are, and who issues them.
- [Mapping: 2017 Trust Services Criteria to ISO 27001](https://www.aicpa-cima.com/resources/download/mapping-2017-trust-services-criteria-to-iso-27001), from the AICPA: the official crosswalk to check the map's ISO column against.
- [SOC 2 readiness track](https://github.com/neon1llc/ready-secure-go/tree/main/content/tracks/soc2), in Ready, Secure, Go: the plain-language introduction this course builds on.
