---
title: "3. Find your real risks"
description: "Run a first risk assessment in an afternoon: what could go wrong, how likely it is, how bad it would be, and who owns each risk."
---

## Why auditors care

SOC 2 expects your controls to answer your risks. Without a record of how you decided what could go wrong, an auditor can't tell whether your controls are the right ones. Do this first, because other controls refer back to it (controls [RISK-01 and RISK-02](../controls/controls-map.md#risk)).

## Method

1. **List what you protect:** customer data, uptime, code, money, and reputation, using the inventory from [module 2](02-scope.md).
2. **List what could go wrong** in plain sentences: "An engineer's laptop is stolen with production keys on it." "A fake invoice gets paid." Include fraud and change, such as a new product, office, big hire, or vendor.
3. **Score likelihood and impact** from 1 to 5, and write down what the numbers mean so next year's scores compare:

   | Score | Likelihood | Impact |
   |---|---|---|
   | 1 | Less than once in ten years | Barely noticed |
   | 3 | About once in a few years | Customers notice, and it costs a bad week |
   | 5 | Expected this year | Lose major customers or the company |

4. **Multiply** for a score from 1 to 25. Anything 12 or above gets a treatment plan now.
5. **Choose a treatment:** *reduce* (add or improve a control), *transfer* (insurance or contract), *avoid* (stop the risky thing), or *accept* (leadership signs off, with a reason).
6. **Name an owner,** a person, not a team, and **set a review date:** at least yearly, and when the business changes.

Run it as a ninety-minute session with leadership, the engineering lead, and whoever handles money and people, starting from a list of fifteen risks. Add a column for the control IDs that reduce each risk. A high risk with no control is a gap, and a control that answers no risk may not be worth keeping.

## Exercise

Copy the [risk register template](../templates/risk-register.csv) and fill in at least fifteen scored risks. Give every risk scored 12 or higher a treatment and an owner, and get leadership to sign off on accepted risks in writing. An email reply is enough.

## Sources

- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework), NIST.
- [2017 Trust Services Criteria, with revised points of focus (2022)](https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022), AICPA.
- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001), ISO. The standard is paid.
