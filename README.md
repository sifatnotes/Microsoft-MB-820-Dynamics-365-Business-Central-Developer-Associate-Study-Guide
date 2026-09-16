# Microsoft-MB-820-Dynamics-365-Business-Central-Developer-Associate-Study-Guide
MB-820 study guide covering AL development, Business Central extensions, tables, pages, reports, APIs, testing, telemetry, integrations, and practical developer labs.
# Microsoft MB-820: Dynamics 365 Business Central Developer Associate Study Guide

## Introduction

This repository is an independent study guide for **Microsoft MB-820: Microsoft Dynamics 365 Business Central Developer** and the **Microsoft Certified: Dynamics 365 Business Central Developer Associate** certification.

It focuses on AL development, Business Central extensions, tables, pages, reports, XMLports, codeunits, queries, permissions, testing, telemetry, REST APIs, OData, and integrations with other applications.

Microsoft's current published skills measured are dated June 10, 2025. [1]

## Exam Overview

| Item | Information |
|---|---|
| Vendor | Microsoft |
| Exam | MB-820 |
| Certification | Microsoft Certified: Dynamics 365 Business Central Developer Associate |
| Level | Intermediate |
| Purpose | Design, develop, test, and maintain Business Central solutions |
| Target candidates | Business Central developers |
| Passing score | 700 or greater |
| Current listed price | $165 USD* |
| Renewal | 12 months |

\*Microsoft states that exam pricing depends on the country or region where the exam is proctored. Verify current pricing before registration. [2]

Microsoft expects candidates to have applied knowledge of Business Central and AL, the development environment, Business Central tools, installation and upgrade concepts, AppSource, and application lifecycle management. [1]

## Who Should Take It?

MB-820 is intended for developers who build and maintain extensions for Microsoft Dynamics 365 Business Central.

Useful background includes:

- AL programming
- Business Central architecture
- Visual Studio Code
- Business Central extensions
- Relational data concepts
- APIs and web services
- Git/source control
- CI/CD
- Testing and debugging
- Microsoft Power Platform integration

Microsoft's official training course is designed for advanced-level learners. [3]

## Exam Objectives / Domains

Microsoft currently measures six domains. [1]

### 1. Describe Business Central — 10–15%

Study:

- Business Central architecture
- Core solution
- Extension model
- Update lifecycle
- Online versus on-premises capabilities
- Base app
- System app
- Business Central apps
- AppSource

### 2. Install, Develop, and Deploy for Business Central — 10–15%

Focus on:

- Development environment
- Visual Studio Code
- AL extension configuration
- `app.json`
- Multiple AL extensions
- Debugging
- Deployment
- Extension maintenance
- Multilanguage development

### 3. Develop by Using AL Objects — 35–40%

This is the largest domain.

Study:

- Role Centers
- Page types
- Page objects
- Page extensions
- Tables
- Table extensions
- Enums
- Reports
- Report layouts
- Document reports
- Processing-only reports
- Report request pages
- XMLports
- Codeunits
- Events
- Triggers
- Interfaces
- Installation codeunits
- Upgrade codeunits
- Permission sets
- Entitlements
- Queries
- Query joins
- Filters
- Aggregations

### 4. Develop by Using AL — 15–20%

Understand:

- Profiles
- Views
- User assistance
- Assisted Setup
- Teaching tips
- In-app tours
- Onboarding checklists
- AL data-process models
- Table types
- Master-data patterns
- Document standards
- Custom procedures
- AL data types
- File handling
- Data manipulation
- Expressions
- Variables
- Built-in functions
- Error handling
- Access modifiers

### 5. Work with Development Tools — 10–15%

Study:

- Business Central testing
- Test Toolkit
- Test codeunits
- Test procedures
- Automated testing
- Telemetry
- Telemetry configuration
- Custom telemetry signals
- Telemetry analysis

### 6. Integrate Business Central with Other Applications — 10–15%

Focus on:

- HTTP classes
- REST services
- JSON
- External APIs
- Business Central APIs
- OData
- Bound actions
- Unbound actions
- Read Scale-Out
- External application integration

These domains and percentages are from Microsoft's current MB-820 study guide. [1]

## Detailed Study Notes

### Business Central Architecture

Understand the relationship between:

**Business Central platform → System app → Base app → Extensions**

The extension model allows developers to add or modify functionality without directly changing the base application.

Understand the differences between:

- Online
- On-premises
- Base app
- System app
- Extensions
- AppSource apps

### AL Development

AL is the primary development language for Business Central.

Become comfortable with:

- Tables
- Pages
- Page extensions
- Table extensions
- Codeunits
- Enums
- Reports
- Queries
- XMLports

A developer should understand both the syntax and the Business Central design patterns behind these objects.

### Tables and Pages

Tables define business data.

Pages provide user interfaces for that data.

Common page types include:

- List
- Card
- Document
- Role Center
- Worksheet

Understand how table extensions and page extensions modify existing functionality.

### Reports

Review:

- Report objects
- Data items
- Request pages
- Report triggers
- Report layouts
- Processing-only reports
- Multilanguage reports
- Document reports

Know when a processing-only report is appropriate versus a report designed for user-facing output.

### Codeunits, Events, and Interfaces

Codeunits contain reusable AL procedures and business logic.

Events allow extensions to respond to application behavior without modifying base code.

Interfaces support interchangeable implementations and help create maintainable solutions.

### Installation and Upgrade

Understand the purpose of:

- Install codeunits
- Upgrade codeunits
- Extension dependencies
- Data migration during upgrades
- Extension versioning

Plan upgrades carefully so application data remains consistent.

### Permissions

Study:

- Permission sets
- Permission set extensions
- Object permissions
- Entitlements
- Inherent permissions

Use least privilege and test permissions using realistic user scenarios.

### Queries

Business Central queries can retrieve and aggregate data without relying only on record variables.

Understand:

- Data items
- Links
- Joins
- Filters
- Columns
- Aggregations

### AL Error Handling

Understand how AL handles:

- Errors
- Validation
- User-facing messages
- Data consistency

Good error handling should help users understand what went wrong without exposing unnecessary implementation details.

### APIs and REST

Understand the flow:

**Business Central ↔ HTTP/REST ↔ JSON ↔ External Application**

Review HTTP classes, JSON handling, API pages, OData, and bound/unbound actions.

### Testing and Telemetry

Use automated tests to validate business logic and extensions.

Telemetry provides operational information that can help developers:

- Diagnose issues
- Detect performance problems
- Understand application behavior
- Monitor custom signals

## Important Concepts

Revise:

- Business Central architecture
- Base app
- System app
- Extensions
- AppSource
- AL
- Visual Studio Code
- `app.json`
- Tables
- Table extensions
- Pages
- Page extensions
- Role Centers
- Enums
- Reports
- Report layouts
- XMLports
- Codeunits
- Events
- Triggers
- Interfaces
- Install codeunits
- Upgrade codeunits
- Permission sets
- Entitlements
- Queries
- Profiles
- Views
- Assisted Setup
- Teaching tips
- AL data types
- Procedures
- Variables
- Error handling
- Test Toolkit
- Test codeunits
- Telemetry
- REST
- HTTP
- JSON
- Business Central APIs
- OData
- Bound actions
- Unbound actions
- Read Scale-Out
- ALM
- Source control
- CI/CD

## Practical Examples / Labs

Use only authorized Business Central environments and test data.

1. Install Visual Studio Code and the AL extension.
2. Connect to a Business Central development environment.
3. Create a basic AL extension.
4. Configure `app.json`.
5. Create a custom table.
6. Create a list page.
7. Create a card page.
8. Extend an existing table.
9. Extend an existing page.
10. Create an enum.
11. Create a codeunit.
12. Subscribe to a Business Central event.
13. Create an interface with multiple implementations.
14. Build a report with a request page.
15. Create a processing-only report.
16. Build an XMLport.
17. Create an AL query with joins and filters.
18. Create a permission set.
19. Create an install/upgrade codeunit.
20. Write automated tests.
21. Run the Business Central Test Toolkit.
22. Add custom telemetry.
23. Call an external REST API.
24. Parse JSON in AL.
25. Create and consume a Business Central API.
26. Experiment with OData actions.
27. Put the extension under Git version control.
28. Create a basic CI/CD pipeline for an AL project.

## Study Strategy

Use Microsoft Learn and the official MB-820 study guide as primary resources.

Combine:

- AL documentation
- Business Central documentation
- Microsoft's MB-820 training
- Visual Studio Code development
- Hands-on extension projects
- Debugging
- Automated tests
- API integration
- Telemetry
- Git/source control
- CI/CD

Microsoft recommends training and hands-on experience before taking the exam. [1]

Spend extra time on **AL objects**, because the largest published domain is Developing by Using AL Objects at 35–40%.

Avoid memorizing code without understanding why a particular Business Central object, event, API, or extension pattern should be used.

## 30-Day Study Plan

**Days 1–3:** Business Central architecture, online/on-premises, base app, system app, extensions, AppSource, and update lifecycle.

**Days 4–6:** Visual Studio Code, AL development environment, `app.json`, workspaces, debugging, and deployment.

**Days 7–13:** Tables, table extensions, pages, page extensions, Role Centers, enums, reports, layouts, XMLports, and codeunits.

**Days 14–16:** Events, triggers, interfaces, install/upgrade codeunits, permission sets, entitlements, and queries.

**Days 17–20:** AL syntax, data types, variables, procedures, expressions, files, data manipulation, errors, profiles, views, and onboarding.

**Days 21–23:** Test Toolkit, test codeunits, automated testing, telemetry, and custom telemetry signals.

**Days 24–27:** HTTP, REST, JSON, Business Central APIs, OData, bound/unbound actions, and external integrations.

**Days 28–29:** Build a complete Business Central extension combining tables, pages, codeunits, permissions, tests, and an API integration.

**Day 30:** Review weak areas, complete Microsoft's Practice Assessment, use the exam sandbox, and revisit the current study guide.

## Common Mistakes

- Confusing tables with pages
- Modifying base functionality when an extension is appropriate
- Ignoring extension dependencies
- Misusing events
- Writing business logic directly in UI objects
- Ignoring permissions
- Confusing install and upgrade codeunits
- Creating inefficient queries
- Skipping automated testing
- Ignoring telemetry
- Hard-coding external API assumptions
- Mishandling JSON
- Ignoring API security
- Using outdated AL syntax or Business Central patterns
- Memorizing code instead of understanding object behavior

## Exam-Day Tips

- Read the complete development scenario.
- Identify the Business Central object being tested.
- Determine whether the requirement calls for a new object or an extension.
- Pay attention to upgrade, permissions, performance, and maintainability requirements.
- For AL questions, understand the execution context of triggers, procedures, and events.
- For integration questions, distinguish REST, APIs, OData, and JSON responsibilities.
- For testing questions, choose approaches that validate behavior rather than implementation details.
- Manage time carefully and revisit flagged questions if possible.
- Microsoft requires a score of **700 or greater** to pass. [1]

## Final Checklist

- [ ] Understand Business Central architecture
- [ ] Know the extension model
- [ ] Comfortable with AL
- [ ] Can configure `app.json`
- [ ] Can create and extend tables
- [ ] Can create and extend pages
- [ ] Understand reports and layouts
- [ ] Can create XMLports
- [ ] Understand codeunits and events
- [ ] Know interfaces
- [ ] Understand install/upgrade codeunits
- [ ] Can configure permissions
- [ ] Understand queries
- [ ] Know AL data types and error handling
- [ ] Understand profiles and onboarding
- [ ] Can write automated tests
- [ ] Understand telemetry
- [ ] Can consume REST services
- [ ] Understand JSON
- [ ] Know Business Central APIs and OData
- [ ] Understand ALM and CI/CD
- [ ] Completed hands-on extension projects
- [ ] Completed Microsoft's Practice Assessment
- [ ] Used the exam sandbox

## Official Resources

- MB-820 Study Guide:
  https://learn.microsoft.com/credentials/certifications/resources/study-guides/mb-820
- Dynamics 365 Business Central Developer Associate:
  https://learn.microsoft.com/credentials/certifications/d365-business-central-developer-associate/
- MB-820 Training:
  https://learn.microsoft.com/training/courses/mb-820t00
- Business Central Documentation:
  https://learn.microsoft.com/dynamics365/business-central/
- AL Development Documentation:
  https://learn.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-dev-overview
- AL Language:
  https://learn.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview
- Business Central APIs:
  https://learn.microsoft.com/dynamics365/business-central/dev-itpro/api-reference/v2.0/
- Microsoft Learn:
  https://learn.microsoft.com/training/

Always verify the latest MB-820 study guide, certification status, pricing, languages, and exam policies directly with Microsoft.

## Voucher / Discount

**Learn SecByte, an official Microsoft reseller partner**, provides certification voucher options and discounts where available.

Learn SecByte's official Black Friday offer provides up to 70% off selected Microsoft exam vouchers.

MB-820 voucher:

https://learn.secbyte.org/vouchers/microsoft-mb-820

Check the current offer and availability before purchasing. Do not assume this specific exam is 70% off unless the current offer explicitly states it. Voucher pricing and availability may change.

## Disclaimer

This is an **independent/community study guide** and is not an official Microsoft certification document. Microsoft, Dynamics 365, Business Central, AL, Power Platform, and related trademarks belong to Microsoft.

Candidates should verify current exam information, objectives, pricing, policies, certification status, and voucher availability directly with Microsoft.

This repository does **not** contain exam dumps, leaked questions, or recalled exam questions. It is intended for legitimate education, hands-on development, and certification preparation only.
