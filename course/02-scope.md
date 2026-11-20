---
title: "2. Draw the boundary"
description: "Choose the system, the criteria, the people, and the vendors your report covers, and handle the providers you rely on."
---

## Scope is a product decision

Your report describes one **system**: the service customers buy, plus the people, processes, software, infrastructure, and data that deliver it. Everything inside gets tested, and customers notice what you leave out. Keep scope as small as the customer's need allows: a first report on the one product customers ask about beats a stalled report on everything.

## What to define

1. **The service,** named as customers name it.
2. **The criteria.** Security is always in. Add others only if customers need them:
   - **Availability** if contracts promise uptime.
   - **Confidentiality** if you hold customer secrets such as designs, financials, or source code.
   - **Processing integrity** if customers rely on your calculations or transactions being correct, as with payroll or billing.
   - **Privacy** if you collect personal information directly from individuals. Most business-to-business companies skip it at first.
3. **The people and infrastructure:** everyone with access to production or customer data, plus cloud accounts, repositories, the identity provider, and tools that touch customer data.

## Vendors you rely on

You can't audit your cloud provider's data center, so the report handles it one of two ways:

- **Carve-out** (most common): the report names the provider as a **subservice organization**, says which of its controls you rely on, and points to its SOC report. You review that report each year (control [VEN-01](../controls/controls-map.md#vendors)).
- **Inclusive:** the provider's controls are tested in your report. This is rare and needs the provider's cooperation.

Every vendor SOC report lists **complementary user entity controls**: things the vendor expects *you* to do, such as two-step sign-in for admin accounts. Your report must show you do them (control [VEN-03](../controls/controls-map.md#vendors)). Yours will list some for your customers too, so start that list now.

## Exercise

Using the [system description outline](../templates/system-description-outline.md), write the scope statement: the service in one sentence, the criteria with a reason for each beyond Security, a diagram of every system that stores or processes customer data, each vendor marked carve-out or not relevant, and three complementary controls your customers must do.

## Sources

- [2017 Trust Services Criteria, with revised points of focus (2022)](https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022), AICPA.
- [SOC suite of services](https://www.aicpa-cima.com/resources/landing/system-and-organization-controls-soc-suite-of-services), AICPA.
