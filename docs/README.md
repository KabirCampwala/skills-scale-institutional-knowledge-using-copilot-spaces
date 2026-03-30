# OctoAcme Project Management Docs

Welcome! This repository serves as the centralized Copilot Space for OctoAcme's program process documentation. Whether you are onboarding to the team or looking for a quick reference on how OctoAcme manages projects, this README is your starting point. All core process documents are located in this `docs/` folder and cover the full project lifecycle—from initiation through retrospective and continuous improvement.

---

## Project Management Processes Overview

OctoAcme follows a lightweight, lifecycle-based project management approach designed to keep delivery iterative and transparent. Work generally moves through five stages: **Initiation** (validate the problem, define measurable outcomes, align stakeholders), **Planning** (turn the approved initiative into an actionable backlog and release plan), **Execution** (build/test/review in small increments), **Release** (deploy with standard checks and rollback readiness), and **Close/Retro** (capture learnings and convert them into improvements). Across all stages, OctoAcme emphasizes customer value, clear ownership (named Project Manager and Product Lead), data-informed decision-making, and psychological safety to encourage learning and early risk surfacing.

Roles are clearly defined to support execution without ambiguity. The **Project Manager (PM)** coordinates delivery mechanics—timelines, risks, dependencies, and stakeholder communications—while the **Product Manager / Product Lead (PdM/Product Lead)** owns outcomes, prioritization, and success measurement. **Developers** implement features, collaborate on design and testability, and contribute estimates and risk identification; **QA/Testing** validates acceptance criteria and quality as needed; and **Stakeholders/Sponsors** provide input, approvals, and escalation support. Key artifacts (the project one-pager/charter, prioritized backlog with acceptance criteria, definition of done, risk register, and retrospective action items) create a shared source of truth throughout the project.

OctoAcme uses consistent communication and execution rhythms to maintain momentum and alignment. Teams typically run **daily standups** focused on progress and blockers, a **weekly delivery sync** for demos/progress and flagged risks, and **sprint/milestone reviews** to validate outcomes. Stakeholder communication is structured via regular updates (weekly or milestone-based) and a standard weekly status template (progress, next steps, risks/blockers, asks/decisions). Risks and dependencies are tracked in a simple **risk register** and reviewed routinely; escalation follows a clear path from team triage to PM coordination with Product Lead and dependent teams, up to sponsor-level escalation for business-impacting issues.

Quality assurance is embedded into day-to-day execution and release practices. OctoAcme encourages a disciplined **PR workflow** (small pull requests when possible, issue links and acceptance criteria in descriptions, CI tests/linting before review, and at least one approval per team policy). Testing expectations include **unit tests** for new logic, **integration tests** where appropriate, and **end-to-end smoke tests** for critical flows prior to release, supported by security scanning in CI and manual QA when needed for feature acceptance. Releases require completion of acceptance criteria, passing checks, release notes, rollback/mitigation planning, and post-deploy verification—helping teams reduce risk while maintaining observability and reliability.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's PM approach and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to validate, scope, and kick off a new project |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, estimation, release planning, and risk identification |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Sprint execution, daily standups, progress tracking, and escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, communication cadences, and status reporting |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release readiness, deployment checklist, rollback planning, and post-deploy verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Sprint/project retros, action item tracking, and process improvement |
| [Roles & Personas](octoacme-roles-and-personas.md) | Descriptions of all roles involved in OctoAcme projects |

---

## Contributing

Have a suggestion or update for one of these process documents? Use the [Add/Update Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose your changes. The template will guide you through describing the update, explaining why it is needed, and identifying which document(s) are affected. All contributions go through a review process to ensure content remains accurate and consistent with OctoAcme's practices.
