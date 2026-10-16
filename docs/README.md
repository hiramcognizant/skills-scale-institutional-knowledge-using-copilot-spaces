# OctoAcme Project Management Docs

## About
OctoAcme project management docs centralize our processes for initiating, planning, executing, releasing, and continuously improving work. These documents capture a lightweight project lifecycle (Initiation → Planning → Execution → Release → Retrospective), core artifacts (one-pager, backlog, risk register, release notes), and decision gates and checklists teams should follow to keep delivery predictable and visible.

## Key workflows & practices
- Project board workflow: Backlog → Ready → In Progress → In Review → QA → Done. Use the board to visualize progress and surface dependencies.
- Pull request discipline: prefer small PRs, link issues and include acceptance criteria, run CI (tests, linting, security scans) before requesting review, and require at least one approval (or team policy) before merging.
- Planning & delivery: timeboxed planning, definition of done (DoD) for pullable work, prioritized backlog items with acceptance criteria and estimates, and sprint demos to validate progress.

## Personas & communication
- Core roles: Project Manager (delivery coordination), Product Manager (prioritization & outcomes), Developers (implementation & tests), QA (validation), and Stakeholders (inputs & approvals).
- Communication cadence: daily standups for blockers, weekly delivery syncs, PM/PdM alignment meetings, sprint demos/reviews, monthly stakeholder updates, and ad-hoc escalations following the documented escalation path.

## Quality & release practices
Quality is ensured through unit and integration tests, end-to-end smoke tests for critical flows, CI-based security scanning, and manual QA when needed. Follow the pre-release checklist (passing CI, release notes, rollback plan, smoke tests) and the deployment checklist when promoting to staging and production.

## Brief overview of OctoAcme project management processes
OctoAcme runs projects through a clear, phase-based lifecycle: Initiation, Planning, Execution, Release, and Retrospective. New initiatives begin with a concise Project One-pager to capture the problem, objective, success metrics, stakeholders, and an initial timeline; a decision gate confirms readiness to plan. Planning translates approved initiatives into a prioritized backlog with acceptance criteria, estimates, and a Definition of Done so that work pulled into iterations is ready and testable.

Day-to-day execution uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request process that favors small PRs, links changes to issues, and requires CI (tests, linting, and security scans) to pass before review and merging. Sprint planning is timeboxed and only items meeting the Definition of Done are pulled; risks and cross-team dependencies are tracked in the Risk Register and discussed in weekly syncs for timely escalation.

Roles and communication are explicit: Product Managers define outcomes and prioritize the backlog, Project Managers coordinate delivery and communications, Developers implement and write tests, QA validates acceptance criteria, and Stakeholders provide input and approvals. Communication cadence includes daily standups for blockers, weekly delivery syncs and PM/PdM alignment, sprint demos for validation, and monthly stakeholder updates. Quality assurance is layered—unit and integration tests, end-to-end smoke tests, CI security scanning, and manual QA when needed—combined with pre-release and deployment checklists to reduce release risk.

## Docs
- octoacme-project-management-overview.md — Overview, principles, roles, and key artifacts
- octoacme-project-initiation.md — Project initiation guide and one-pager template
- octoacme-project-planning.md — Planning activities, backlog templates, and checklists
- octoacme-execution-and-tracking.md — Team rhythm, workflows, and execution checklist
- octoacme-release-and-deployment.md — Release types, pre-release and deployment checklist
- octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and action tracking
- octoacme-risks-and-communication.md — Risk register, communication templates, and escalation
- octoacme-roles-and-personas.md — Role summaries and responsibilities

## How to use
- Link this README from the repository README and use it as the single entry point to process documentation in docs/.
- To propose changes, open an issue using the "Add Content to Project Management Process Docs" template and reference the document to update.

---

*This README was added to centralize OctoAcme process documentation and improve discoverability for team members and new hires.*

<!-- PR note: docs/add-readme-pr — minor edit to create a branch diff for PR -->
