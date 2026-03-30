# OctoAcme — RACI Matrix

## Purpose
Clarify who is **Responsible**, **Accountable**, **Consulted**, and **Informed** for each major activity in the OctoAcme project lifecycle. Use this matrix to resolve ambiguity about ownership and communication expectations.

## RACI Key

| Letter | Meaning |
|--------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; final decision authority |
| **C** | **Consulted** — provides input before or during the activity |
| **I** | **Informed** — notified when the activity is complete or status changes |

> Each activity should have exactly **one A** (accountable owner). Multiple Rs are allowed.

---

## Project Lifecycle RACI

| Activity | Project Manager | Product Manager | Developer | QA / Testing | Stakeholder / Sponsor |
|----------|:-:|:-:|:-:|:-:|:-:|
| **Initiation** | | | | | |
| Define problem statement & business case | C | A | C | — | C |
| Create Project One-pager / Charter | R | A | C | — | I |
| Stakeholder alignment & sign-off | R | C | — | — | A |
| Decision gate: approve to move to planning | C | A | — | — | C |
| **Planning** | | | | | |
| Run project kickoff meeting | A | C | C | C | I |
| Create and prioritize backlog | C | A | R | C | I |
| Define Definition of Done (DoD) | R | A | R | R | I |
| Estimate scope and capacity | C | C | A | C | — |
| Create release plan and milestone map | A | C | C | C | I |
| Set up project board and repo structure | R | C | A | C | — |
| Draft initial risk register | A | C | C | — | I |
| **Execution** | | | | | |
| Daily standup facilitation | A | I | R | R | — |
| Implement features and fixes | — | C | A | C | — |
| Code review and PR approval | C | — | A | C | — |
| Write and maintain automated tests | — | — | R | A | — |
| Track progress and update project board | A | I | R | R | I |
| Escalate blockers (Level 2+) | A | C | R | R | I |
| Update risk register | A | C | C | — | I |
| **Release** | | | | | |
| Release readiness sign-off | A | C | C | R | I |
| QA sign-off and smoke tests | C | — | C | A | — |
| Deploy to staging | C | — | A | R | — |
| Deploy to production | C | — | A | R | I |
| Announce release to stakeholders | A | C | — | — | I |
| Post-deploy verification | C | — | R | A | I |
| Incident response and rollback | A | I | R | R | I |
| **Close & Retrospective** | | | | | |
| Facilitate retrospective | A | C | R | R | I |
| Document action items and owners | A | C | R | R | — |
| Track and close improvement action items | A | C | R | R | I |
| Project close report / final stakeholder update | A | C | — | — | I |

---

## Notes
- **"—"** indicates no regular involvement for that role in that activity; involvement may still occur situationally.
- Activities with no "A" assigned should be flagged to the PM immediately.
- Update this matrix at the start of each project if roles differ from defaults (e.g., developer doubles as QA on a small team).

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
