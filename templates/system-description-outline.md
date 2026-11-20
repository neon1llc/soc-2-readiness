---
title: System description outline
description: "Headings for drafting the system description that opens a SOC 2 report, and the scope decisions behind it."
---

Draft this in [module 2](../course/02-scope.md) and refine it before the audit. The auditor helps shape the wording, but the facts are yours.

## 1. The company and the service

Who you are, what the service does, and who uses it, in one or two paragraphs.

## 2. Principal service commitments and system requirements

What you promise customers about security (and availability or confidentiality, if in scope) in contracts, SLAs, and your trust page, then the system requirements that make those promises true.

## 3. Components of the system

- **Infrastructure.** Cloud providers, regions, accounts, networks. A diagram helps.
- **Software.** Applications, databases, and the main tools that support them.
- **People.** Teams and roles, and roughly how many people.
- **Procedures.** How the work is done: access, change, operations, incidents.
- **Data.** What data the system holds, where, and its classification.

## 4. Boundaries

What's in scope, what's out, and why.

## 5. Criteria in scope

Security, plus any of Availability, Confidentiality, Processing Integrity, and Privacy, with a reason for each.

## 6. Subservice organizations

Each provider, what it does, whether it's carved out, and the controls you rely on it for.

## 7. Complementary user entity controls

What customers must do for your controls to work, such as managing their own users and protecting their credentials.

## 8. Significant changes during the period

A new system, a new provider, a reorganization, or anything else major.

## 9. Incidents

Significant incidents that affected your commitments.

## Sources

- [SOC suite of services](https://www.aicpa-cima.com/resources/landing/system-and-organization-controls-soc-suite-of-services), from the AICPA: what the SOC reports are and who issues them.
- [2017 Trust Services Criteria, with revised points of focus (2022)](https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022), from the AICPA: the criteria SOC 2 reports measure against.
