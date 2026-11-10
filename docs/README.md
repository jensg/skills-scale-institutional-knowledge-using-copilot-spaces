# OctoAcme Project Management Docs

A guide to how OctoAcme initiates, plans, executes, releases, and improves projects. These documents provide shared processes, roles, and artifacts for cross-functional work.

## Project management process summary

OctoAcme follows a customer-focused, iterative project lifecycle. Work begins by validating the business need, defining measurable outcomes, identifying stakeholders, and deciding whether to proceed. Once approved, the team plans prioritized, shippable increments with clear acceptance criteria, owners, estimates, milestones, dependencies, and a Definition of Done.

During execution, teams track work on a project board and coordinate through standups, delivery syncs, demos, and regular stakeholder updates. The Project Manager (PM) coordinates delivery, schedules, risks, dependencies, and communications; the Product Manager (PdM) defines outcomes, prioritizes the backlog, and measures success; developers design, build, and test; QA/testing validates quality and acceptance; and stakeholders provide input and approvals. Risks and blockers are reviewed regularly and escalated from the team through the PM and Product Lead to the sponsor when needed. A project README or release document serves as the single source of truth for status.

Quality is integrated throughout delivery: teams use unit tests for new logic, integration tests where applicable, smoke tests for critical flows, security scanning, and manual QA when needed. Pull requests should be small where possible, link to an issue and acceptance criteria, pass automated tests and linting before review, and receive at least one approval or meet the team’s defined policy. Releases require acceptance criteria and CI/security checks to pass, release notes and rollback or mitigation plans to be ready, and post-deployment verification. Retrospectives after sprints, releases, milestones, or incidents capture learnings and track a small number of measurable improvement actions.

## Documentation

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, roles, key artifacts, lifecycle, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — Validate and authorize proposed work, align stakeholders, and prepare the initial project one-pager.
- [Project Planning](octoacme-project-planning.md) — Turn approved initiatives into prioritized backlogs, delivery plans, milestones, and risk/dependency tracking.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day delivery rhythm, project-board and PR workflows, quality practices, metrics, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk lifecycle, stakeholder updates, incident communications, and escalation paths.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Release readiness, deployment checks, rollback, incident response, and release notes.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Run retrospectives and track measurable improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — Responsibilities, goals, and communication patterns for developers, product managers, and project managers.
