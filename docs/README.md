# OctoAcme Project Management Docs

## About
OctoAcme project management docs centralize our processes for initiating, planning, executing, releasing, and continuously improving work. These documents capture the project lifecycle (Initiation → Planning → Execution → Release → Retrospective), core artifacts (one-pager, backlog, risk register, release notes), and the lightweight decision gates and checklists teams should follow to keep delivery predictable and visible.

## Key workflows & practices
- Project board workflow: Backlog → Ready → In Progress → In Review → QA → Done. Use the board to visualize progress and surface dependencies.
- Pull request discipline: prefer small PRs, link issues and include acceptance criteria, run CI (tests, linting, security scans) before requesting review, and require at least one approval (or team policy) before merging.
- Planning & delivery: timeboxed planning, definition of done (DoD) for pullable work, prioritized backlog items with acceptance criteria and estimates, and sprint demos to validate progress.

## Personas & communication
- Core roles: Project Manager (delivery coordination), Product Manager (prioritization & outcomes), Developers (implementation & tests), QA (validation), and Stakeholders (inputs & approvals).
- Communication cadence: daily standups for blockers, weekly delivery syncs, PM/PdM alignment meetings, sprint demos/reviews, monthly stakeholder updates, and ad-hoc escalations following the documented escalation path.

## Quality & release practices
Quality is ensured through unit and integration tests, end-to-end smoke tests for critical flows, CI-based security scanning, and manual QA when needed. Follow the pre-release checklist (passing CI, release notes, rollback plan, smoke tests) and the deployment checklist when promoting to staging and production.

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
- To propose changes, open an issue using the "Add Content to Project Management Process Docs" template (/.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) and reference the document you want to update.

---

*This README was added to centralize OctoAcme process documentation and improve discoverability for team members and new hires.*
