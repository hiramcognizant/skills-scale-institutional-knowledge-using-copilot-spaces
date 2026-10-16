# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testing

### Role Summary
QA/Testing validates the product against acceptance criteria and helps maintain product quality through automated and manual testing.

### Responsibilities
- Define test plans and test cases
- Execute manual and automated testing
- Work with developers on regression and integration tests
- Verify acceptance criteria and report issues

### Typical Communication
- Test status in delivery syncs
- QA notes in PRs and issues

---

## Stakeholders

### Role Summary
Stakeholders provide inputs, requirements, and approvals. They represent business, customer, or partner perspectives.

### Responsibilities
- Provide feedback and sign-off on acceptance criteria
- Help prioritize and approve scope changes
- Participate in demos and milestone reviews

---

## Additional personas proposed for clarity and accountability

The following personas are proposed to be added to docs/octoacme-roles-and-personas.md to improve clarity of ownership, handoffs, and cross-team coordination.

### Delivery Engineer
- Responsibilities: Own and maintain CI/CD pipelines, deployment automation, build/release tooling, environment provisioning, and core observability instrumentation.
- Interactions: Partners with Developers to make deployments reliable and repeatable; works with QA to provision test environments and automate smoke tests; coordinates with the Release Manager and Project Manager on deployment windows and rollback readiness.
- Example deliverables: CI/CD pipeline configs, deployment runbooks, environment templates, observability dashboards.

### Technical Program Manager (TPM)
- Responsibilities: Drive cross-team coordination for complex, multi-team initiatives; map and manage dependencies; maintain milestone schedules and risk mitigation plans.
- Interactions: Works with Product Managers on scope and trade-offs; coordinates with Project Managers on scheduling and resourcing; liaises with engineering leads to unblock cross-team technical dependencies.
- Example deliverables: Dependency maps, milestone plans, cross-team status reports.

### UX Researcher / Designer Representative
- Responsibilities: Provide user research, validate designs against success metrics, and communicate UX implications to the delivery team.
- Interactions: Partners with Product Managers to translate research into acceptance criteria; works with Developers to clarify visual/interaction details; assists QA in defining UX-related acceptance checks.
- Example deliverables: Research findings, usability checklists, design specs, user validation reports.

### Security Liaison
- Responsibilities: Coordinate security reviews, ensure scanning tools and remediation workflows are in place, and surface security requirements during planning and release.
- Interactions: Works with Developers to remediate findings; collaborates with CI/Duty owners to enforce scans; advises Product/Project Managers on scope and timelines for remediation.
- Example deliverables: Security review notes, remediation tickets, security gating checklists.

### Data Analyst / Measurement Lead
- Responsibilities: Define success metrics, implement measurement plans, validate telemetry, and analyze outcomes to inform product decisions.
- Interactions: Partners with Product Managers to set goals and metrics; works with Developers to instrument code and with stakeholders to report outcomes and insights.
- Example deliverables: Dashboards, metric definitions, A/B analysis summaries.

### Release Manager
- Responsibilities: Own release orchestration and readiness, produce release notes, verify rollback and mitigation plans, and coordinate cross-functional release activities.
- Interactions: Coordinates with Project Manager, Delivery Engineer, QA, Support and Security to ensure releases meet readiness criteria.
- Example deliverables: Release checklists, release notes, rollback/runbook documents.

### Support / Operations Liaison
- Responsibilities: Represent support and operations in planning; define on-call, alerting, and post-release runbook requirements; own escalation contacts.
- Interactions: Works with Release Manager and Developers to ensure monitoring and alerts are in place; communicates operational constraints to PMs; coordinates post-release support handoff.
- Example deliverables: Runbooks, on-call contact lists, operational readiness reports.

---

## How to use these persona definitions
- Include persona representatives on relevant planning and release checklists.
- For each project, indicate which personas are assigned or consulted and list deliverables they are responsible for.
- Track persona-driven action items in the project backlog so ownership is clear.
